# Basic-Version-Control

## What is Version Control?
Version control is a system that records changes to a set of files over time, enabling you to track and manage modifications, collaborate with others and revert to previous states. It maintains a history of changes and is very helpful in the software development process by facilitating coordination in a controlled and organized way. A popular example is Git.

## Difference between Git and GitHub
- Git is a distributed version control system (DVCS) while GitHub is a web based platform that extends Git's functionality.
- Git operates locally while GitHub operates remotely.
- Git doesn't provide remote hosting, GitHub is a remote hosting service

## GitHub alternatives:
- GitLab
- BitBucket
- SourceForge
- Gitea
- AWS CodeCommit
- RhodeCode
- Perforce Helix Core

## Difference between git fetch and git pull:
'git fetch' and 'git pull' are both Git commands used to update your local repository with changes from a remote repository but they have different purposes.
- git fetch:
    - Retrieve changes from the remote repository without merging them into your working branch.
    - Used to review changes before merging
- git pull:
    - Used to fetch changes from the remote repository and automatically merge them into the current branch.
    - Used if one wants to fetch and merge changes in a single command.

## Git rebase:
This command is used to change the order or apply new changes to the existing commit history in your Git repository. It is often used to make your commit history cleaner and more linear. Basically it is used to integrate changes from a base branch(like 'main'). 
### Note:
    Git rebase changes commit history so be cautious with this command if you have shared your branch with others
### Command Syntax:
    "git rebase [target-branch]"

## Git cherry-pick:
This is a Git command that allows you to apply a specific commit from one branch to another. It's useful when you want to pick and choose individual commits from one branch and apply them to another branch.
### Note:
    Be cautious with cherry-picking if the commit you are picking depends on other changes that are not present in the target branch. You might need to resolve conflicts.
### Command Syntax:
    "git cherry-pick [stepppp]"



