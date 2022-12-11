---
title: "Git in Github"
teaching: 30
exercises: 15
questions:
- "How should we manipulate data?"
objectives:
- "Define git vocabulary (commit, fork, pull request, repository, commit message)."
- "Demonstrate ability to navigate through a GitHub repository main page."
- "Define the difference between a directory and a repository."
- "Create a repository on GitHub."
- "Demonstrate ability to commit changes to text files with a commit message."
- "Evaluate repository History."
- "Create a pull request to someone else's repository."
keypoints:
- "Keep raw data read only."
- "Manipulate data in a reproducible manner"
output:  
      html_document
---


> ## Requirements
> - Must have a GitHub account.
>
{: .prereq}

> ## Overview
> 1. In this activity you are going to learn how to collaborate using GitHub. With a partner you will learn some basics which allow you to share and edit files on GitHub.
> 1. Create a git repository hosted at GitHub
> 1. Build README.md file
> 1. Commit changes to repository
> 1. Collaborate by forking and editing partners file
> 1. Explore GitHub features: graphs, diff, blame, ect.
{: .keypoints}

## Step-by-Step
### Create a repository with a `README.md` file
Follow along with your instructor and perform these steps:
1. Go to your GitHub profile. The url should be http://github/your-user-name.
1. Create a new GitHub repository, click the green "new" button, under the repositories tab.
1. Name your repository work-organization-your-name
1. In the details write "tips to organizing research".
1. Click the initiate a README.md file option.

### So far
- A repository is a directory (folder) that houses both the files of a project AND the git history of the project.
- Once the repository is created you will be directed to the repository page which now has its own web address.
- Each repository on GitHub has a unique url so you can easily share.
- The git history is a detailed history of all the changes made to that file. One of the features of using GitHub is the ability to view your repository history which are displayed in the Graphs section of your GitHub repository page.
- At this point in the git history of your work-organization-your-name repository there is only one commit.

### Edit the README.md file
- Go back to the work-organization-your-name repository main page. Click on `README.md`, then click "edit this file". Add the following information into the readme.md file:
  - Name?
  - What kind of scientist do you you tell people you are at dinner parties?
  - In the past month, what are the three main activities you have been doing at work?
  - What are the three most important tools/strategies you use for organizing your work?
  
*tip*: Notice that you can use markdown syntax. Use [this guide](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/) for GitHub's flavor of `Markdown`. Use the "Preview" button to view the formatting of your `README.md` file.

### Commit
- Commit takes a snap shot of your project. Each commit includes a commit message that concisely defines changes made or project state at the time of the commit.

1. Summarize the changes that you have made in 50 characters or less and click the green "commit button".
1. Check out the git history. You should now see two commits.

## Edit and collaborate with your partner
### Collaborate
Now it is time to collaborate with your partner. Navigate to your partner's repository by typing the url directly into your address bar. In order to edit someone else's repository you usually follow this simplified work flow:
1. Fork their repository to your user account
1. Make edits and commit
1. Create a pull request that merges your changes into their repository.

_tip_: Depending on the project there are variations on the above work flow. Often the rules for contributing to a project are outlined in a file called `CONTRIBUTING.md` within the repository. One of the more often used works flows is [GitHub Flow](https://guides.github.com/introduction/flow/).

### Forking
- **Forking** creates a copy of a git repository into your own account.
- Forking allows you to make changes to a repository without affecting the main repository of the project.
- This is one of the most exciting aspects of GitHub - you essentially encouraged to copy and play with anyone's code!

1. To fork your partner's repository click the "Fork" button in the top left hand part of your screen.
1. When it asks where you would like to fork the repository, choose your user account (if you are new to GitHub, this should be the only option).

### Make edits and commit
- You should now have a copy of your partners repository, `work-organization-their-name`.
- GitHub keeps track of the entire git history of the project and all forked copies made of the project.

1. Edit your partners repository by clicking the edit button.
1. Paste in the answers to your questions under theirs and make a commit.

### Create a pull request
- A **pull request** is the final step in the collaboration process, essentially asking if the edits made to your copy can be incorporated into another repository.

1. Make sure you are in your copy of your partner's repository by looking at the url - your user name should preface the repository name.
1. Click the green "New Pull Request" button. You will get an overview of the changes you made to the repository.
1. Click the "Create a Pull Request" button to continue the pull request. Your partner will now get a notification of a pull request on their main repository, as will you if your partner made changes.
1. Accept this pull request.

### Explore GitHub features
Now that you have accepted the pull request. Take a few minutes to explore the git history using the "Graphs" section of the repository.

### Extra Exercise *after* class:

- Find a way to practice by contributing more. You don't have to be a great at programming to help with projects. Many projects are in need of spelling or general editing. There is a whole Twitter community that helps beginner git users find projects to practice using git.

- Check it out if you want to contribute to more projects: https://twitter.com/yourfirstpr.

- If you are interested in practicing this process try adding a quote to this repository: https://github.com/TheCodingCollective/quotes.

> ## Overview
> RStudio and version controls
> - Git
> - Subversion
>
> For this lesson we will focus on git
{: .objectives}  

### RStudio projects (required for version control):
- RStudio projects make it straightforward to divide your work into multiple contexts, each with their own working directory, workspace, history, and source documents.

## Step-by-Step
1. Fork the `rr-version-control-demo` repository.
1. Clone your forked repository to obtain a local copy of the files into an RStudio project.
1. Edit a file in this repository/project.
1. Stage your changes to be committed.
1. View the diff, and commit your changes, with a commit message.
1. Push your changes to your own fork of the the `rr-version-control-demo` GitHub repository.

### Step 1: Fork
- Go to the [`rr-version-control-demo`](https://github.com/Reproducible-Science-Curriculum/rr-version-control-demo).
- Click on Fork (on the top right corner).

_Now you have a copy of_ `rr-version-control-demo` _repository in your account, woohoo!_

#### Aside - where am I?
**How can I tell if I am looking at my fork or the original repository?**
- Look at the URL
- Look at the name of the repo on the upper left corner, for your fork it will say:

`[your-github-name]/rr-version-control-demo`

`forked from Reproducible-Science-Curriculum/rr-version-control-demo`

### Step 2: Clone
- In RStudio, go to "File", and then "New Project"
- Click on "Version Control": Checkout a project from a version control repository
- Click on "Git": Clone a project from a repository
- Fill in the info:
  - URL: use HTTPS address
  - Create as a subdirectory of: Browse to where you would like to create this folder

### Step 3: Edit
- Open the file called gdp-life-expectancy.Rmd and `knit`.
- Change the analysis_year to another year for which we have data (1952, 1957, 1962, 1967, 1972, 1977, 1982, 1987, 1992, 1997, 2002, 2007), and `knit` again. Examine the output for changes.

### Step 4: Stage
- Go to the Git pane in RStudio.
- Stage the changes for `gdp-life-expectancy.Rmd` and `gdp-life-expectancy.html` by checking the boxes next to then, and hit `Commit`.

_Don't worry about the other files that appear in this pane, we'll get to them in a bit._

### Step 5: Commit
- In the pop-up window view the diff for the `.Rmd` file. You can view it for the HTML file as well if you like.
- Enter an **informative** commit message, like "Changed analysis year to X", and hit Commit.

### Step 6: Push
**push**: When using git push always means pushing commits from your local respository (your computer) to a remote repository (GitHub).
- Now push your changes to GitHub by hitting `Push`.
- Enter login information as needed.
