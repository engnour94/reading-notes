# Introduction to Git
What is the Git?
Git is a distributed version-control system for tracking changes in any set of files, originally designed for coordinating work among programmers cooperating on source code during software development.
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it. Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.
Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.
Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

##States

Files in Git can reside in three main states: committed, modified and staged.

**Committed**: Data is securely stored in a local database
**Modified**: File has been changed but not committed to the database
**Staged**: Flagged a file’s changed version to be committed in the next snapshot
![stages]( https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

## Getting Started
**Download Git**
You should make sure you have the latest version.
Git can be installed in three ways:
* Install as a package
* Install via another installer
* Download and compile the source code.

**Graphical Clients**
Git includes inherent Graphical User Interface (GUI) tools. However, users can also utilize third-party tools created for particular platforms.
GUI Clients
You can access a variety of GUI clients via the following link:

https://git-scm.com/downloads/guis

**Initial Customization**
you should perform some customization steps, which should only need to be completed once on any machine. To change settings, you can repeat these steps.
* Configuration of Variables
An inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.

* Identity Setting
After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.

**Default Text Editor**
Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:

$ git config --global core.editor emacs

Note: For some editors, you may need to find specific instructions for default configuration.

**Check Settings**
To check settings, use the git config --list command.

Example:

$ git config --list

user.name=Jane Smith

user.email=example@email.com

color.status=auto

color.branch=auto

color.interactive=auto


**Getting Help**
There are three ways to get more information on a particular command, by accessing the manual:

git help command

git command --help

man git-comman


**Setting up a Git Repository**
* Importing: To import an existing project or directory into Git, follow these steps using the Terminal or Command Line
* Cloning: You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL.

##Workflow
Local Repository Structure
The local Git repository has three components:

Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit
![workflow]( https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)
Saving Changes
All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

**The Life Cycle of File Status**
After you edit a file, Git flags it as modified because of changes made after the previous commit.
You stage the modified file.
Then, you commit staged changes
![ The Life Cycle of File Status]( https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)
1. Tracking and Staging a New File
2. Committing a File or all changes
3. Pushing Changes

