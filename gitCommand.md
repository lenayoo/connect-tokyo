#Git commands
https://www.atlassian.com/git/glossary#commands

1. git add : Moves changes from the working directory to the staging area. This gives you the opportunity to prepare a snapshot before committing it to the official history.

2. git branch : This command is your general-purpose branch administration tool. It lets you create isolated development environments within a single repository.

3. git checkout : In addition to checking out old commits and old file revisions, git checkout is also the means to navigate existing branches. Combined with the basic Git commands, it’s a way to work on a particular line of development.

4. git clone : Creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.

5. git commit : Takes the staged snapshot and commits it to the project history. Combined with git add, this defines the basic workflow for all Git users.

6. git commit --amend : Passing the --amend flag to git commit lets you amend the most recent commit. This is very useful when you forget to stage a file or omit important information from the commit message.

7. git config : A convenient way to set configuration options for your Git installation. You’ll typically only need to use this immediately after installing Git on a new development machine.

8. git fetch : Fetching downloads a branch from another repository, along with all of its associated commits and files. But, it doesn't try to integrate anything into your local repository. This gives you a chance to inspect changes before merging them with your project.
