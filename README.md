# Git lesson

This lesson covers the basics of version control.

This lesson is for the first day of the MSSE bootcamp (chem 280).

To make a commit ("verion" or "checkpoints") of your files, follow this procedure:

1. Make changes to your projects that you would like to keep.
2. When you have your changes, tell `git` you are ready to create a checkpoint of the using `git add FILENAME` command.
3. Create a checkpoint of your file using `git commit -m "Message about what you did`.

## Adding Features
Features should be developed on branches.
To create and switch a branch, use the command

`git sitch -c NEW_BRANCH_NAME`

To switch to an existing branch, use

`git switch BRANCH_NAME`