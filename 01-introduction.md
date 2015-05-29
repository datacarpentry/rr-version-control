# Version Control via Git and Github

Before this lesson:

-  Obtain a Github account. If you sign up using a student email you get five free private repositories through a [student developer pack](https://education.github.com/pack).
- Install Github GUI. [Github GUI Guide (Mac)](https://mac.github.com), [Github GUI Guide (Windows)](https://windows.github.com). 

After this lesson, you should be able to:

## Learning Objectives

- Define version control as a way to save 
- Recognize the difference between Git and hosting Git 
- Benefits of Git (working alone)
- Benefits of Git (collaboration) 
- Locate further resources for understanding best practices of Git

## Lesson Plan Outline

Goal:  Host `pick4country.Rmd` to Github repository. [Original Directory](https://github.com/Reproducible-Science-Curriculum/rr-organization1/tree/master/files/lit-prog)


## Why Version Control?

Using a software tool to handle the versions of your project files
lets you focus on the more interesting/innovative aspects of your project

> ## Learning Objectives {.objectives}
>
> *   Understand the benefits of an automated version control system.
> *   Understand the basics of how Git works.

We'll start by exploring how version control can be used
to keep track of what one person did and when.
Even if you aren't collaborating with other people,
automated version control is much better than this situation:

[![Piled Higher and Deeper by Jorge Cham, http://www.phdcomics.com](fig/phd101212s.gif)](http://www.phdcomics.com)

"Piled Higher and Deeper" by Jorge Cham, http://www.phdcomics.com

We've all been in this situation before: it seems ridiculous to have multiple nearly-identical versions of the same document. Some word processors let us deal with this a little better, such as Microsoft Word's "Track Changes" or Google Docs' version history.

Version control systems start with a base version of the document and then save just the changes you made at each step of the way. You can think of it as a tape: if you rewind the tape and start at the base document, then you can play back each change and end up with your latest version.

![Changes are saved sequentially](fig/play-changes.svg)

Once you think of changes as separate from the document itself, you can then think about "playing back" different sets of changes onto the base document and getting different versions of the document. For example, two users can     make independent sets of changes based on the same document.

![Different versions can be saved](fig/versions.svg)

If there aren't conflicts, you can even try to play two sets of changes onto the same base document.

![Multiple versions can be merged](fig/merge.svg)

A version control system is a tool that keeps track of these changes for us and
helps us version and merge our files. It allows you to
decide which changes make up the next version, called a
[commit](reference.html#commit), and keeps useful metadata about them. The
complete history of commits for a particular project and their metadada make up
a [repository](reference.html#repository). Repositories can be kept in sync
across different computers facilitating collaboration among different people.

> ## The long history of version control systems {.callout}
>
> Automated version control systems are nothing new. Tools like RCS, CVS, or
> Subversion are considered now legacy systems, offering more limited
> capabilities than modern tools, such as Git and
> [Mercurial](http://swcarpentry.github.io/hg-novice/). In particular, the
> latter are *distributed*, meaning that they don't need a centralized server
> to host the repository.

## Version Control Features

*   It's easy to set up
*   Every copy of a Git repository is a full backup of a project and its history
*   A few easy-to-remember commands are all you need for most day-to-day version control tasks
*   The [GitHub](https://github.com/) hosting service provides a web-based collaboration service

## Two main concepts

*   *commit*: a recorded set of changes in your project's file
*   *repository*: the history of all your project's commits

## Why Use Github?

*   No need for a server: easy to set up
*   GitHub's strong community: your colleagues are probably already there

## Learning Objectives {.objectives}

*   Explain what remote repositories are and why they are useful.
*   Clone a remote repository. 
*   Push to or pull from a remote repository.

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
to hold those master copies;
we'll explore the pros and cons of this in the final section of this lesson.


## Attribution and Licenses

This material was remixed from 
- [Software Carpentry Git Novice Lesson](http://swcarpentry.github.io/git-novice/) - Copyright © Software Carpentry. All Software Carpentry instructional material is made available under the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/). The following is a human-readable summary of (and not a substitute for) the full legal text of the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/legalcode).
- [Jenny's Test Drive R Markdown Lesson](http://stat545-ubc.github.io/block007_first-use-rmarkdown.html)
- [Jenny's Install Git](https://stat545-ubc.github.io/git01_git-install.html)



