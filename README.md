# Git Basics

Git is a version control system that allows you to track changes and collaborate on projects efficiently. Here are the essential Git commands to get you started:

## 1. Initialize a Git Repository

To start using Git in a project, navigate to the project's root directory in your terminal/command prompt and run the following command:

`git init`

This creates a new Git repository in your project folder.

## 2. Add and Commit Changes

To track changes in your project, you need to add files to the staging area and then commit them. Use these commands:

`git add <file> # Add a specific file to the staging area`

`git add . # Add all changes in the current directory to the staging area`

`git commit -m "Your commit message here"`

The commit message should briefly describe the changes you made.

## 3. Check Repository Status

To see the current status of your repository, use the following command:

`git status`

This shows which files have been modified, added to the staging area, or committed.

## 4. View Commit History

To view the commit history and see a list of previous commits, run:

`git log`

This displays a chronological list of commits, with their commit IDs, dates, and commit messages.

## 5. Create and Switch Branches

Branches allow you to work on new features or fixes without affecting the main codebase. To create a new branch and switch to it, use:

`git checkout -b <branch-name>`

Replace `<branch-name>` with the name of your new branch.

## 6. Merge Branches

After you've finished working on a feature or fix in a branch, you can merge it back into the main branch (usually called `master` or `main`). First, switch to the main branch:

`git checkout <main-branch-name>`

Then, merge your feature branch into the main branch:

`git merge <branch-name>`

This combines the changes from the specified branch into the main branch.

## 7. Push to Remote Repository

To share your changes with others or back up your code, you can push your local repository to a remote repository (like GitHub or GitLab). First, add the remote repository URL:

`git remote add origin <remote-url>`

Then, push your changes:

`git push -u origin <branch-name>`

Replace `<remote-url>` with the URL of your remote repository and `<branch-name>` with the branch you want to push.

These are the fundamental Git commands to get started. Git offers many more features for collaboration and code management, but with these basics, you can effectively track changes, create branches, and collaborate on your projects.
