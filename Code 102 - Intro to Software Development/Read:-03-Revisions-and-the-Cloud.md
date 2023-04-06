# Read: 03 - Revisions and the Cloud

**What is Version Control?**

Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

**What is cloning in Git?**

Primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.

**What is the command to track and stage files?**

Single File
Track one file only by using the following format:
git add filename
All Files
Track all files in a repository by using the following command:
$ git add *
*After using these commands, files are tracked and staged for committing.
After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:
$ git status

On branch master

Changes to be committed:

  (use "git reset HEAD ..." to unstage)
new file: EXAMPLE
This information tells us that there are changes to be committed and that the file has been staged.

**What is the command to take a snapshot of your changed files?**

Git Commit

**What is the command to send your changed files to Github?**

The git add comma
