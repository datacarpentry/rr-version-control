# Version Control via Git and Github

## Learning Objectives

* Define version control. 
* Understand the basics of how Git works.
* Understand the benefits of using a software tool to handle the versions of your project files, icluding working alone and in collaboration.
* Recognize the difference between Git and hosting Git 

## Why Version Control?

By now you should be see that reproducibility making conscious decisions 
about organization of your project, which in turn results in a customized 
workflow.  A project changes dramatically through time, and even the 
most organized project 
is prone to chaos if every detail of change is not recorded properly. You 
could record these changes by hand or you can use version control. Using a 
software tool, like Git, that handles the versions of 
your project files frees you from tedium in recording changes and lets you 
focus on the interesting/innovative aspects of your project.

We'll start by exploring how version control can be used
to keep track of what one person did and when.
Even if you aren't collaborating with other people,
automated version control is much better than this situation:

[![Piled Higher and Deeper by Jorge Cham, http://www.phdcomics.com](fig/phd101212s.gif)](http://www.phdcomics.com)

"Piled Higher and Deeper" by Jorge Cham, http://www.phdcomics.com

We've all been in this situation before: it seems ridiculous to have multiple 
nearly-identical versions of the same document. Some word processors let us deal 
with this a little better, such as Microsoft Word's "Track Changes" or Google Docs' 
version history.

Version control systems start with a base version of the document and then save just 
the changes you made at each step of the way. You can think of it as a tape: if you 
rewind the tape and start at the base document, then you can play back each change 
and end up with your latest version.

![Changes are saved sequentially](fig/play-changes.svg)

Once you think of changes as separate from the document itself, you can then think 
about "playing back" different sets of changes onto the base document and getting 
different versions of the document. For example, two users can 
make independent sets of changes based on the same document.

![Different versions can be saved](fig/versions.svg)

If there aren't conflicts, you can even try to play two sets of changes onto 
the same base document.

![Multiple versions can be merged](fig/merge.svg)

A version control system is a tool that keeps track of these changes for us and
helps us version and merge our files. It allows you to
decide which changes make up the next version, called a
**commit**, and keeps useful metadata about them. The
complete history of commits for a particular project and their metadata make up
a **repository**reference.html. Repositories can be kept in sync
across different computers facilitating collaboration among different people.

### Version Control Features

*   It's easy to set up
*   Every copy of a Git repository is a full backup of a project and its history
*   A few easy-to-remember commands are all you need for most day-to-day version control tasks
*   The [GitHub](https://github.com/) hosting service provides a web-based collaboration service

##Remote Hosting your Git projects

Git is the version control system, it keeps track of all the changes in the directory.  
Remote hosting sites, like Github or Bitbucket, allow you to store your directories.

### Features of using a Hosting Service Like Github

*   Backup of your project
*   No need for a server: easy to set up
*   GitHub's strong community: your colleagues are probably already there
*   Provides tools to help enhance collaboration
*   A common location to share off your work

Version control really comes into its own
when we begin to collaborate with other people.
We already have most of the machinery we need to do this;
the only thing missing is to copy changes from one repository to another.

Systems like Git allow us to move work between any two repositories.
In practice,
though,
it's easiest to use one copy as a central hub,
and to keep it on the web rather than on someone's laptop.
Most programmers use hosting services like
[GitHub](http://github.com),
[BitBucket](http://bitbucket.org) or
[GitLab](http://gitlab.com/)
to hold those master copies.

## Attribution and Licenses

This material was remixed from 

*   [Software Carpentry Git Novice Lesson](http://swcarpentry.github.io/git-novice/) - Copyright © Software Carpentry. All Software Carpentry instructional material is made available under the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/). The following is a human-readable summary of (and not a substitute for) the full legal text of the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/legalcode).


