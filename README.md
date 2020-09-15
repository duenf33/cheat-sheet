# Cheat-Sheet

* ## Git Clone:
When you create a repository on your GitHub Enterprise Server instance, it exists as a remote repository. You can clone your repository to create a local copy on your computer and sync between the two locations.

`~: git clone  https://github.com/yourname/example`

Forking is a concept while cloning is a process. Forking is just containing a separate copy of the repository and there is no command involved. Cloning is done through the command ‘git clone‘ and it is a process of receiving all the code files to the local machine.

**[Cloning vs Forking Link](https://www.toolsqa.com/git/difference-between-git-clone-and-git-fork/)**

* ## Git Status:
The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. Status output does not show you any information regarding the committed project history.

`~: git status`

* ## Git Log:

By default, with no arguments, git log lists the commits made in that repository in reverse chronological order; that is, the most recent commits show up first. As you can see, this command lists each commit with its SHA-1 checksum, the author’s name and email, the date written, and the commit message.

`~: git log`

SHA1 is a cryptographic hash function, which means that given the data, it will creates a 40-digit hexadecimal number (the ones you can see when you do git log )

* ## Git Add:
  
When you use git add you are essentially saying “Here are a few files that I’ve changed” and I like to think of it as placing them into an open package.  Now that you have placed your files into the box we need to seal it up before we can send it on its way.

`~: git add filename.md example.md`

* ## Git Commit: 

When you create a commit the system will file this away into the history of your project with a unique reference code. You can look up this code later and it will pull up the message (or packing slip) that you wrote when you used the git commit command.

> **[Things you probably didn't know about Git](https://medium.com/@bencabanes/things-you-probably-didnt-know-about-git-f0fbdb86a071)**

`~: git commit -m "Comments on changes made"`

* ## Git Push: 

Git push is most commonly used to publish an upload local changes to a central repository. After a local repository has been modified a push is executed to share the modifications with remote team members.

`~: git push`

