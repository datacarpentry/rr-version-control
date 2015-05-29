# Version Control via Git and Github

**Before this lesson**:

-  Obtain a Github account. If you sign up using a student email you get five free private repositories through the [student developer pack](https://education.github.com/pack).
- Install Github GUI. [Github GUI Guide (Mac)](https://mac.github.com), [Github GUI Guide (Windows)](https://windows.github.com). 

After this lesson, you should be able to:

*   Initiate Git in a project directory.
*   
*   Push to or pull from a remote repository.
*   Clone a remote repository.

## Activity

**Goal**: to host the beautiful Rmarkdown document, `countryPick4.Rmd`, on github. Find the folder named `lit-prog` which was downloaded yesterday for the Organization lesson. 

*tip*: With Git comes many strong opinions on the best practices of how to use Git, which can seem very intimidating. The truth is Git can be really straight forward to use and best practices only really develop while using it. This tutorial will strive to show you Git as simply as possible, while guiding you where to further learn more about best practices. 

### Part 1: Initiate Git in the `lit-prog` directory

1. Find your `lit-prog` directory. Know where it is.
2. Open the GitHub GUI.  Click the `+` in the top left corner of the screen, choose `add`, and either enter the path to the `lit-prog` or click `choose` to find the folder on your computer.  To complete click `create and add repository`.

![Initiating Git](fig/git-GUI-01.png)

Now you have initiated Git into that directory you have created a `Git repository`, which is a folder or directory that is now being tracked by Git software. 

### Part 2: Commit 

At this point we have just initiated Git.  You can see in the "History" tab that this repository has no history.  History only begins by making a **commit**.  Git is all about composing and saving snapshots of your project and then working with and comparing those snapshots. A commit is taking a snapshot, while attaching a little note to help you navigate to why that instance of the project is important.  

Let's go ahead and make a commit. All you have to do is add a message that describes your commit and press "Commit to master". 

![Commit](fig/git-GUI-02.png)

Now if you see that "Changes" tab is blank and if you look at "History", you can view your first commit. 

*tip*: There are many beliefs on best practices of committing.  The best advice is: Commit early and often. Then strive to describe your commit concisely, but with meaning. You want to be able to understand exactly what point of the project you are in months from now. 

### Part 3: Changing files

Open up the `countryPick4.Rmd` and add your name to the YMAL front matter at the top of the document, then Save.

    ---
    title: "Pick four - comparing trends in population  over time"
    output: pdf_document
    Author: Ciera Martinez
    ---

Now if you look at the "Changes" tab you can see that the line I added is clearly displayed in green.  You may also notice that that is all there is, since I did not change anything else. 

![Viewing Changes](fig/git-GUI-03.png)

Go ahead and commit this change.

###Summary 


## Push to Github

Log in to GitHub, then click on the icon in the top right corner to create a new repository and 

![Creating a Repository on GitHub](fig/github-create-repo-01.png)

name it `lit-prog-firstName-lastName`. For example, `lit-prog-ciera-martinez`. Then click "Create Repository".

![Creating a Repository on GitHub](fig/github-create-repo-02.png)

As soon as the repository is created,
GitHub displays a page with a URL and some information on how to configure your local repository:

![Creating a Repository on GitHub](fig/github-create-repo-03.png)

The next step is to connect the two repositories. We do this by making the GitHub repository a remote for the local repository. The home page of the repository on GitHub includes the string we need to identify it:

II. Activity 
    1.  Sign up for Github.  
    2.  Open the Github GUI.
    -   Set up new repo.
    -   Commit Changes. 
    -   Push to Github.
    -   Repeat 5 and 6.
    -   Partner up and pull from each other's repo.    
    -   Change the file. 
    -   Submit Pull Request.
3. Introduction to best practices and troubleshooting (Lecture-ish) (Branching, Dev. branch, CONTRIBUTING.md, Workflows, Conflicts, ect.) 

## Resources

-   [Github GUI Guide (Mac)](https://mac.github.com/help.html)
-   [Github GUI Guide (Windows)](https://windows.github.com/help.html)
-   [Bitbucket](https://bitbucket.org/) - alternative to Github hosting. Unlimited free 

### Repositories to practice pushing and pulling

-   [https://github.com/grayghostvisuals/Practice-Git](https://github.com/grayghostvisuals/Practice-Git)
-   [https://github.com/TheCodingCollective/quotes](https://github.com/grayghostvisuals/Practice-Git)
-   [https://bitbucket.org/tutorials/tutorials.bitbucket.org](https://github.com/grayghostvisuals/Practice-Git)
 
### Examples of code from research papers on Github

-   [https://github.com/tessington/PNASForageFish](https://github.com/tessington/PNASForageFish)
-   [https://github.com/seananderson/paleobaselines/](https://github.com/seananderson/paleobaselines/)

### Best Practices

-   [Nice Overview of Best Practices](https://sethrobertson.github.io/GitBestPractices/)
-   [Git Flow CheatSheet](http://danielkummer.github.io/git-flow-cheatsheet/)

## Attribution and Licenses

This material was remixed from 
- [Software Carpentry Git Novice Lesson](http://swcarpentry.github.io/git-novice/) - Copyright © Software Carpentry. All Software Carpentry instructional material is made available under the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/). The following is a human-readable summary of (and not a substitute for) the full legal text of the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/legalcode).
- [Jenny's Test Drive R Markdown Lesson](http://stat545-ubc.github.io/block007_first-use-rmarkdown.html)
- [Jenny's Install Git](https://stat545-ubc.github.io/git01_git-install.html)



