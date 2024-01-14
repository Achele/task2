# Table of content

- [Explain Version control](#explain-version-control)
- [Explain difference between git and github](#difference-btw-git&github)
- [List three other github alternatives](#other-github-alternativest)
- [Explain the difference between git fetch and fit pull](#Explain-the-difference-between-git-fetch-and-fit-pull)
- [Explain in simple terms git rebase and the command for it](#Explain-in-simple-terms-git-rebase-and-the-command-for-it)
- [Explain in simple terms git cherry-pick and the command for it](#Explain-in-simple-terms-git-cherry-pick-and-the-command-for-it)

## Explain Version control

Version control, also known as source code management (SCM) or revision control, is a system that records changes to files over time. It enables developers to track and manage modifications to their code, collaborate with others seamlessly, and revert to previous states if needed. The primary purpose of version control is to maintain a history of changes made to a project's files, providing a structured and efficient way to manage code development.

## Explain difference between git and github

Git is a distributed version control system that helps track changes in source code during software development. GitHub, on the other hand, is a web-based platform that provides hosting for Git repositories. In essence, Git is the tool for version control, while GitHub is a service that utilizes Git for collaborative software development, offering features like issue tracking, pull requests, and more.

## List three other github alternatives

- GitLab: Similar to GitHub, GitLab is a web-based platform for version control and collaboration, offering features like CI/CD pipelines, code review, and more.

- Bitbucket: Provided by Atlassian, Bitbucket supports both Git and Mercurial. It offers features such as branching strategies, pull requests, and integration with other Atlassian products.

- SourceForge: An older platform, SourceForge provides version control, bug tracking, and collaboration tools. It supports various version control systems like Git, Mercurial, and Subversion.

## Explain the difference between git fetch and fit pull

git fetch and git pull are both Git commands, but they serve different purposes.

- git fetch: This command fetches changes from a remote repository to your local repository, but it does not automatically merge them with your working branch. It updates your local references, allowing you to see what changes exist on the remote without integrating them into your local branch.

- git pull: This command, on the other hand, fetches changes from a remote repository like git fetch, but it also automatically merges those changes into your current branch. It's a combination of git fetch followed by git merge, or it can be configured to use rebase instead of merge.

## Explain in simple terms git rebase and the command for it

git rebase is a command used to integrate changes from one branch into another. It rewrites the commit history to make it appear as if you've been working on the changes directly on the current branch.

Here's the basic command for git rebase:

`git rebase <branch-name>`

This command takes the changes from the specified branch and applies them on top of your current branch. It can help create a cleaner, linear history and resolve potential conflicts more efficiently. However, use it with caution, especially when collaborating with others, as it modifies the commit history.

## Explain in simple terms git cherry-pick and the command for it

git cherry-pick is a command that lets you pick specific commits from one branch and apply them onto another branch.

Here's the basic command for git cherry-pick:

`git cherry-pick <commit-hash>`

This command takes the changes introduced by the specified commit and applies them to your current branch. It's useful when you want to bring in specific changes without merging entire branches. Just be aware that cherry-picking can lead to conflicts, especially if the changes you're picking interfere with the current state of your branch.
