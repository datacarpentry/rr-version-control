# Collaborative Version Control via *only* Github

These are notes are for teaching git collaboration through *only* Github (no local clients). Not putting files onto participants' machines reduced problems that occur from using different operating systems and does not require any local software installation.

This basis of this lesson is this [this suggestion](https://github.com/Reproducible-Science-Curriculum/rr-version-control/issues/4) from Ciera Martinez ([@iamciera](https://github.com/iamciera)), despite the initial commit coming from Karen Cranston ([@kcranston](https://github.com/kcranston)).

## The Activity

Everything is isolated to a `README.md` file. The activity goals are 1. Intro to Git and Github, 2. allow them to share ways in which they organize their work, and 2. allow them to practice Markdown syntax.  I chose organizing their work as a subject matter because I wanted them to get tips from each other and generate discussion. I was with mostly molecular biologists, so the activity encouraged non-computational organization too. I felt asking for how they organized their computational work might intimidate them. Also, I love talking about notebooks!

Intro After showing them how our rrhack group collaboratively made our curriculum material, I discussed motivation and general outline of version control ect. Then went straight into activity.

Total time spent: 2 hours, but we were all pretty chill and experimenting a lot.  Could be less.

### Steps of Activity

-   Have everyone go to their GitHub profile page (Everyone should already have a GitHub account, because you included that in the setup instructions for the workshop, right?)
    +   Introduce the main features of the home page.
-   Create new repository.
    +   call it `work-organization-yourName`
    +   In the details write "tips to organizing research".
    +   make sure they initiate a `README.md file`. Once the repository was created, again show them around the page, highlighting that they have made one commit with the addition of the `README.md` file and explaining that all that they are looking at is a directory with one file.
-   Edit the file.  Click on `README.md`, then click "edit this file".
-   Add the following information into the `readme.md` file (allow ~15 minutes):
    +   Name?
    +   What kind of scientist do you you tell people you are at dinner parties?
    +   In the past month, what are the three main activities you have been doing at work?
    +   What are the three most important tools/strategies you use for organizing your work?

    Have them use at least one hyperlink, bullet point/number set, header, and display at least one picture to practice markdown. Do guide them to the preview changes option to help them along, and paste this [Markdown help](https://help.github.com/articles/markdown-basics/) link into the etherpad.

-   Commit.
    +   Talk about commit messages.
    +   Show them where the repository is. Show them the repository has a url address that is composed of their user name and repository name.
-   Fork a partners Github repository.
    +   The easiest way to have them find each other is typing directly into url.  The search for user option only works if they verified their address through email and many times they do not.
-   Edit forked repository by pasting in their questions below the originals. Commit.
-   Create Pull request.
-   Accept pull request.
-   Look at cool Github features.
    +   Look at Blame, Issues, Wiki, Repo graphs, ect..  Show another cool repository example, like maybe the ReXML repository.
-   Get excited about collaborating on Github.
-   If there is time, you can demo how to clone, edit, commit and push a repository on your own machine, either using the GUI client or CLI (or maybe show cloning a repo in RStudio?)

Of course afterward I had to reiterate what they are not doing. I gave them the references on how to learn more AND repositories to practice.  
