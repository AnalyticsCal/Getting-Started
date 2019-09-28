# Table of Contents

- If you are familiar with git then go [here](#workflow)
- [Getting Started](#getting-started)
    - [Setting up softwares](#setting-up-softwares)
    - [Setting up git](#setting-up-git)
    - [Commands](#commands)
        - [Forking and Cloning](#forking-and-cloning)
        - [Creating branches](#making-branches)
        - [Editing files](#editing-files)
        - [Adding and commiting changes](#adding-and-commiting-changes)
        - [Pushing changes and submitting a Pull Request](#pushing-changes-and-submitting-a-pull-request)
        - [Keeping your fork synced with this repository](#Keeping-your-fork-synced-with-this-repository)
    - [Workflow](#workflow)
- [Resources](#resources)

# Getting Started

### *** For the entire project we will use Python and the code will be hosted in Github. ***

If you get stuck, ask for help on the [AnalyticsCal Slack Channel](https://analyticscal.slack.com/).

## Setting up softwares

The first task is to install git on your machine. For Windows users, download git from here - https://git-scm.com/downloads ans use `git bash`. For Linux users, you can use your distro's package manager to install git.

**Note:** You can learn about Version Control Systems (VCS) [here](https://www.atlassian.com/git/tutorials/what-is-version-control).

Ubuntu VM image can be downloaded from [here](https://www.dropbox.com/sh/ixamttjhpjxtxy8/AABS6e4llSZCKkNxFpPEqZ5ta?dl=0)

## Setting up git

After installing git, run git and execute these commands:

```
git config --global user.name "[name]"
git config --global user.email "[email address]"
```

That should complete the software setup.

## Commands
### Forking and Cloning

```
git clone [copied url here]
```

That should download the repo locally.

### Creating branches

To see a list of branches:

```
git branch
```

To checkout a branch

```
git checkout [branch name here]
```

To checkout and create new branch

```
git checkout -b [branch name here]
```

You should see the branch name change on the terminal prompt.

### Adding and commiting changes

```
git add -A 
```

This adds all files to the upcoming commit. Now, to create the commit run this command:

```
git commit -s -m "[commit message here]"
```

Write any message in place of the commit message.

### Pushing changes and submitting a Pull Request

To push your changes, run:

```
git push origin [branch name]
```

This should upload your changes to your GitHub account. \
Now, you can propose these changes to the actual project by clicking on the **Pull Request** button on GitHub.

### Keeping your fork synced with this repository
The best way to do it (guide by https://codeburst.io/) :\
Go to **step 7 [here](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940)**

## Workflow

- Please **fork** repo before editing and **clone** it to your local machine.(**fork** is a copy of the repo in your account and a **clone** is a copy downloaded into your local machine).
- Create a separate new branch and name it `dev [team number]` and start editing. Please do not edit in the `master` branch and `dev` branch of other team.(team number is used instead of team name to keep the length of branch name short.)
- Adding and commiting : **Sign** the commits you make (using`git -s -m "[Commit message]"`). Please write concise and understandable commit message.
- After commiting check the status, if everything is clean **push** everything to your repo and make a pull request.
- Every time you start working again **Fetch** the repo and start working so that your local repo will be in synchronization with the master.Follow [this](#Keeping-your-fork-synced-with-this-repository)

# Resources

You can learn more about Git and GitHub here:

- https://www.atlassian.com/git/tutorials
- https://www.youtube.com/playlist?list=PLWKjhJtqVAbkFiqHnNaxpOPhh9tSWMXIF 
- https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940

# Acknowledgement

This guide is written by referring to [Arya Das's guide to getting started with open source](https://github.com/aryadas98/Getting-Started)
