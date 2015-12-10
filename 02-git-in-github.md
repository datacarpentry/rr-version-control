# Collaborative Version Control via *only* Github

## Learning Objectives

At the end of this module you should be able to 

1. Define git vocabulary (commit, fork, pull request, repository, commit message).
2. Demonstrate ability to navigate through a Github repository main page. 
3. Define the difference between a directory and a repository.
3. Create a repository on GitHub.
4. Demonstrate ability to commit changes to text files with a commit message.
5. Evaluate repository History.
6. Create a pull request to someone else's repository.

## Activity Overview

In this activity you are going to learn how to collaborate using Github.  With a partner you will learn some basics which allow you to share and edit files on Github. 

## Create a repository with a README.md file (10 minutes)

First we are going to create a repository within our Github user account. Follow along with your instructor and perform these steps:

Go to your Github profile.  The url should be http://github/your-user-name.
  To create a new Github repository, click the green "new" button, under the repositories tab.

    +   name your repository `work-organization-your-name`
    +   In the details write "tips to organizing research".
    +   click the initiate a `README.md file` option. 

Once the repository is created you will be directed to the repository page which now has its own web address. Each repository on Github has a unique url so you can easily share. A **repository** is a directory (folder) that houses both the files of a project AND the git history of the project. The git history is a detailed history of all the changes made to that file.  One of the features of using Github is the ability to view your repository history which are displayed in the Graphs section of your Github repository page. At this point in the git history of your `work-organization-your-name` repository there is only one commit.

## Edit the `README.md` file (10 minutes)

Go back to the `work-organization-your-name` repository main page. Click on `README.md`, then click "edit this file". Add the following information into the `readme.md` file:

    +   Name?
    +   What kind of scientist do you you tell people you are at dinner parties?
    +   In the past month, what are the three main activities you have been doing at work?
    +   What are the three most important tools/strategies you use for organizing your work?

Notice that you can use markdown syntax. Use [this guide](https://help.github.com/articles/markdown-basics/) for Github's flavor of Markdown. You can also use the "Preview" button to view the formatting of your readme.md file. Try to incorporate markdown formating. Github automatically renders Markdown when displaying the file. 

Now it is time to commit. **Commit** takes a snap shot of your project. Each commit includes a commit message that concisely defines changes made or project state at the time of the commit. Summarize the changes that you have made in 50 characters or less and click the green "commit button".  Check out the git history.  You should now see two commits.

### Edit collaborate with your partner (15 min) 

Now it is time to collaborate with your partner.  Navigate to your partner's repository by typing the url directly into your address bar. In order to edit someone else's repository you usually follow this simplified work flow: 

1. Fork their repository to your user account 
2. Make edits and commit 
3. Create a pull request that merges your changes into their repository. 

*tip* Depending on the project there are variations on the above work flow. Often the rules for contributing to a project are outlined in a file called `CONTRIBUTING.md` within the repository. One of the more often used works flows is[Github Flow](https://guides.github.com/introduction/flow/). 

**Forking**. Forking is creating a copy of a git repository into your own account.  This is important because it allows you to make changes to a repository without affecting the main repository of the project.  This is one of the most exciting aspects of Github - you essentially encouraged to copy and play with anyone's code! To fork your partner's repository click the "fork" button in the top left hand part of your screen.  When it asks where you would like to fork the repository, choose your user account (if you are new to Github, this should be the only option).

**Make edits and commit**. You should now have a copy of your partners repository, `work-organization-their-name`. With Git, Github keeps track of the entire git history of the project and all forked copies made of the project. Let's edit by adding to your copy of your partners repository by clicking the edit button.  Paste in the answers to your questions under theirs and make a commit. 

**Create a pull request**.  A pull request is the final step in the collaboration process.  A pull request is essentially asking if the edits made to your copy can be incorporated into another repository. Make sure you are in your copy of your partner's repository by looking at the url - your user name should preface the repository name. Click the green "New Pull Request" button. You will get an overview of the changes you made to the repository. Click the "Create a Pull Request" button to continue the pull request. Your partner will now get a notification of a pull request on their main repository, as will you if your partner made changes. Go ahead and accept this pull request. 

Now that you have accepted the pull request.  Take a few minutes to explore the git history using the Graphs section of the repository. 

## Extra Exercise after class:

If you are interested in practicing this process try adding a quote to this repository: [https://github.com/TheCodingCollective/quotes](https://github.com/TheCodingCollective/quotes).

Find a way to practice by contributing more. You don't have to be a great at programming to help with projects.  Many projects are in need of spelling or general editing. There is a whole Twitter community that helps beginner Git users find projects to practice using git.  Check it out if you want to contribute to more projects: [https://twitter.com/yourfirstpr](https://twitter.com/yourfirstpr).




