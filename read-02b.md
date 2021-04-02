# Git:
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project, called commit.
Git mostly relies on local operations because most necessary information can be found in local resources.
Every single change applied to any file or directory is tracked by Git.
Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data.
Files in Git can reside in three main states: committed, modified and staged.

## Graphical Clients:
Git includes inherent Graphical User Interface (GUI) tools,users can also utilize third-party tools created for particular platforms.
## Initial Customization:
After making sure Git has been installed,you can repeat these steps:
* Configuration of Variables
  * An inherent Git tool called **git config** allows the setting of configuration variables that control aspects of Git’s operation and look.
* Identity Setting
  * users should immediately set the user name and email address.
     * git config --global user. name "name"
     * git config --global user.email "@email.com"
## Default Text Editor:
Git use the system’s default editor, To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:
 * git config --global core.editor emacs

 ## Check Settings:
  * use the git config --list command.
  * to Getting Help, use: git help command

## Setting up a Git Repository:
  1. Switch to the target project’s directory: cd = change directory, cd (path)
  2. Use the git init command
  3. start tracking these repository files, perform an initial commit by typing the following:

    * git add *.c
    * git add LICENSE
    * git commit -m “message”

## Cloning:   
to create a copy of an existing Git repository from a particular, use the clone command with a repository’s URL:
 * git clone (repo.)URL   Note: >repo.>code>HTTPs>copy the link

## Local Repository Structure:
![](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

## The Life Cycle of File Status:
![](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

## Check File Status:
to determine the state of files, utilize the git status command:
## Tracking and Staging a New File
*Single File:*

git add filename

*All Files:*

$ git add *

## Committing a File:
After staging one or multiple files, you should commit the changes and record what you did within the commit message:

* $ git commit **-m “msg”**
* Committing All Changes:  **$ git commit -a**

## Pushing Changes:
push changes to a remote repository: **$ git push origin main**
This command pushes changes from the local “master” branch to the remote repository named “origin”.

## Stashing Changes:
$git stash, This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the $git stash apply command to retrieve the hidden changes.

## Seeing Your Remotes:
* By running the $git remote command, you can view the short names, such as       origin, of all specified remote handles.

* By using $git remote -v, you can view all the remote URLs next to their corresponding short names.
 

## Version Control:
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.

**Local Version Control:**
A Local VCS entails one database on your hard disk that stores changes to files.

**Centralized Version Control:**
(CVCS). This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process.

**Distributed Version Control:**
A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS, To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

