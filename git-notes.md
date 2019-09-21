# Git & GitHub

## What is Version Control System?

A version control system is a database that stores changes over files in a specified directory. There are multiple version control systems, the most known one is Git.

## Basic Commands to work on Git

To initialize a git repository:

```shell
git init
```

When initialized the repo, every change in a file that wants to be versioned leads to be added with:

```shell
git add <filename>
```

If all changes in all files want to be saved, the `.` keyword from Shell can be used instead:

```shell
git add .
```

Then the changes must be commited with a comment:

```shell
git commit -m "This explains the change done"
```

To see the repo status (if there is any unstaged change):

```shell
git status
```

To push the changes to a remote repository:

```shell
git push
```

## Binary files and Plain text files

Files with plain text are files that only contains unformatted text. They can be written by notepad, nano editor, and any other text editor like VS Code or Sublime, these ones are also text editors but especially made to edit code.

Binary files are files that are encoded into a binary system, so they can not be read by any of the mentioned applications.

**Important**: Git and GitHub take version control of only plain text files. It means that if an image or any other binary file is stored in a repository, Git won't keep track of changes made to it. GitHub allows the cloud storage of the file, but it doesn't trace their changes either.



