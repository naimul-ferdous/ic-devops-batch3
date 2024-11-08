# Git Assignment 1

This is git assignment 1 by Naimul Ferdous

## Basic Commands

- `git init`: Initialize a new Git repository in the current directory.
- `git clone <repository-url>`: Clone an existing Git repository from a remote URL.
- `git add <file>`: Stage changes in the specified file for the next commit.
- `git add .`: Stage all changes in the current directory for the next commit.

    ![Add](SS/Add.png)

- `git commit -m "commit message"`: Create a new commit with the staged changes and the provided commit message.

    ![Commit](SS/Commit.png)

- `git push`: Upload the local repository changes to the remote repository.

    ![Push](SS/Push.png)

- `git pull`: Download the latest changes from the remote repository and merge them into the local repository.

## Branching and Merging

- `git branch`: List all local branches.
- `git branch <branch-name>`: Create a new branch with the specified name.
- `git checkout <branch-name>`: Switch to the specified branch.
- `git merge <branch-name>`: Merge the specified branch into the current branch.
- `git branch -d <branch-name>`: Delete the specified local branch.
- `git push origin :<branch-name>`: Delete the specified remote branch.

## Inspection and Comparison

- `git status`: Show the current status of the repository, including unstaged and untracked files.
- `git log`: Show the commit history of the current branch.

    [Log](SS/Log.png)

- `git diff`: Show the differences between the working directory and the staging area.
- `git diff <branch1> <branch2>`: Show the differences between two branches.

## Undoing Changes

- `git reset <file>`: Unstage the specified file.
- `git reset --hard`: Discard all changes in the working directory and staging area.
- `git revert <commit-hash>`: Create a new commit that undoes the changes introduced by the specified commit.
- `git checkout -- <file>`: Discard changes in the working directory for the specified file.

## Remote Repositories

- `git remote add origin <repository-url>`: Add a new remote repository with the name "origin".
- `git remote -v`: Show the configured remote repositories.
- `git push -u origin <branch-name>`: Push the specified branch to the remote repository and set it as the upstream branch.
- `git fetch`: Download objects and refs from the remote repository without merging them into the local repository.
- `git remote prune origin`: Remove references to remote branches that no longer exist.

Remember, these are just the most common Git commands. Git has many more features and commands that you can explore as you become more familiar with the tool.