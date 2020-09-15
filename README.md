# cheat-sheet

* ## Git Clone:
When you create a repository on your GitHub Enterprise Server instance, it exists as a remote repository. You can clone your repository to create a local copy on your computer and sync between the two locations.

`~: git clone  https://github.com/yourname/example`

Forking is a concept while cloning is a process. Forking is just containing a separate copy of the repository and there is no command involved. Cloning is done through the command ‘git clone‘ and it is a process of receiving all the code files to the local machine.

**[Cloning vs Forking Link](https://www.toolsqa.com/git/difference-between-git-clone-and-git-fork/)**

* ## Git Status
The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. Status output does not show you any information regarding the committed project history.

`~: git status`

* ## Git Log

By default, with no arguments, git log lists the commits made in that repository in reverse chronological order; that is, the most recent commits show up first. As you can see, this command lists each commit with its SHA-1 checksum, the author’s name and email, the date written, and the commit message.

`~: git log`

SHA1 is a cryptographic hash function, which means that given the data, it will creates a 40-digit hexadecimal number (the ones you can see when you do git log )

* ## Git Add
  
`~: git add filename.md example.md`