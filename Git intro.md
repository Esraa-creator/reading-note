Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.

 Through version control, one can revert a file or project to a previous version,
 track modifications and modifying individuals, and compare changes.

 A Local VCS entails one database on your hard disk that stores changes to files.
Centralized Version Control System (CVCS). This system entails a single server storing all changes and file versions, 
which can be accessed by various clients.

DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace
 any lost information.

Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores  a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk.

Every single change applied to any file or directory is tracked by Git.

States:

Files in Git can reside in three main states: committed, modified and staged.

Committed

Data is securely stored in a local database

Modified

File has been changed but not committed to the database.

Git can be installed in three ways:

Install as a package
Install via another installer
Download and compile the source code

After making sure Git has been installed, you should perform some customization steps, like Configuration of Variables and Identity Setting.

To import an existing project or directory into Git,Use the git init command.

You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL.

The command that makes a copy of the target repository in a directory named “mydirectory.

The local Git repository has three components:

Working Directory: The actual files resides.
Index: The area used for staging
Head: Points to the most recent commit.

Tracked files can be modified, unmodified, or staged;while Untracked files were not in  the last snapshot and do not currently reside in the staging area.

To determine the state of files, utilize the git status command.

Track one file only by using git add,while tracking all files using $ git add *
After staging one or multiple files, you should commit the changes and record what you 
did within the commit message .

git push :This command pushes changes from the local “master” branch to the remote repository named “origin.
This command temporarily removes changes and hides them, giving you a clean working directory.
 When you are ready to continue working on the changes, simply use the git stash apply command
 to retrieve the hidden changes.
Teams can use remote repositories to push information to and pull data from.
Git will automatically give the name “origin” to the server from which you cloned and 
the name “master” to your local branch.

 all the remote URLs next to their corresponding short names.

Fetching entails pulling data that you don’t have from a remote project.
git push:To push your changes from your local “master” branch upstream to the “origin” server.
use the git remote rm command:To remove a remote .