Git vs Github / local vs Remote / Clone / Commit / ACP / VCS / Deployment

[Code 102 Table of Contents](CodeFellows_102.md)

[<== Home](README.md) 🏠 [Forward ==>](html_markup_semantics_wireframe_personas_meta_content_element_tag_attribute_structure_vs_presentation.md)

## Reading Notes

:electron: [GIT MASTER CHEAT](https://overapi.com/git)

:mortar_board: [Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#4_1)

:books: [Git Community Book](http://alx.github.io/gitbook/)

:zap: [**GUI Client Downloads**] (https://git-scm.com/downloads/guis)


| ***States*** | Files in Git can reside in three main states: committed, modified and staged. |
| :-: | - |
| **Committed** | Data is securely stored in a local database |
| **Modified** | File has been changed but not committed to the database |
| **Staged** | Flagged a file’s changed version to be committed in the next snapshot |

> **Comit=** 'snapshot' / Timeline / '*save as*

**There are three ways to get more information on a particular command,
by accessing the manual:**

1. **git help** *command*
2. git *command* **--help**
3. **man git-** *command*

# Revisions and the Cloud

## Local Repository Structure

**The local Git repository has three components:**

1. **Working Directory**: The actual files reside here.
2. **Index**: The area used for staging
3. **Head**: Points to the most recent commit

> **MVN** Mode Vision Manager - This manages NPM

> **Homebrew** - (install updates for this often **)

> **NodeJs** - Ties into NVM

> **Git** - allows access to github from local computer

> **VSCode** code editor

> **Visual Studio** huge package that is a complete IDE (Integrated Development Environment) it's a Tool being utilzed between the Terminal and GitHub

## Vocabulary


| **Term** | **Context** |
| :-: | - |
| VCS | **Version Control** is a **system** that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified. |
| Local | Many years ago, programmers created**Local Version Control systems**. A Local VCS entails one database on your hard disk that stores changes to files. |
| CVCS | The need for collaboration within a developer team on a single file or set of files led to the advent of the**Centralized Version Control System (CVCS)**. This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process (by eliminating the need to involve all local databases), allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges. |
| Git | (version control system) Git is a DVCS that stores data in a file system made up of***snapshots***. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it. |
| Remote Repositories | In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from. |
| Cloned Repositories | As mentioned earlier, for cloned repositories, Git will automatically give the name*“origin”* to the server from which you cloned and the name*“master”* to your local branch. |
| Remote Clone | In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from. |
| ACP | **ADD-COMMIT-PUSH** *This is the flow for making changes to the repository from the Terminal* |
| Deployment | Git is a very popular version control system used to implement development workflows. The Cloudways Platform allows you to deploy code to your application from your git repositories. Your git repository must support git over SSH for this to work. |

## Steps to setup GitHub deployment

1. Go to your project's Code & Deploys page, in the Repository tab.
2. Click the CONNECT TO GITHUB button to connect your project with GitHub. ...
3. Connect to one of your GitHub repositories. ...
4. Configure the deploy options. ...
5. Deploy your project.  |

## Cloning

**You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:**

> $ git clone https://github.com/test

By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

**To clone a repository into a directory with another name of your choosing, use the following command format:**

> $ git clone https://github.com/test mydirectory

The command above makes a copy of the target repository in a directory named “mydirectory.”

> **Dummy guide Beginning to end** :books:

1. ***Create*** a repo *This happens on GitHub* [Ensure to include a README file]
2. ***Copy*** the hyperlink of the repository from GitHub [ https ]
3. [From the Terminal] **git clone "paste coppied repository https address here"**
4. **ls** will now show the **README** file
5. **code .** opens *Visual Studio*
6. *Make the changes you wish to see happen out in the real world*
7. **git status** at this phase will show you a RED Modified message
8. **git add .** [adds all changes]
9. **git status** at this phase will show you a GREEN Modified message
10. **git commit -m** "this is where you state WHY you've made changes"
11. **git status** at this phase will convey modifications that have been made
12. **git push origin main** This PUSHES from terminal to interwebs
13. **git pull origin main** This PULLS from interwebs to Terminal
14. **git remote -v** shows you connected origin repository web address (fetch) (push)

[Code 102 Table of Contents](CodeFellows_102.md)

[<== Home](README.md) 🏠 [Forward ==>](html_markup_semantics_wireframe_personas_meta_content_element_tag_attribute_structure_vs_presentation.md)
