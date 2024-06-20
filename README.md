Git:Git is a version control system for managing source code
Github: Github is  a web-based platform that provides hosting for Git repositories. It's a web-based Git repository manager that provides access control, collaboration features, bug tracking, and many other tools for software development.
 
Always do - git pull origin master

local->tracking->staged->remote

Local to track= by  file add
track to  stage=  commit
Stagee to remot= git remote add origin <link https>

git init - This command is used to initialize a new Git repository in the current directory. It creates a hidden .git directory that stores all the version control information for the repository.

git clone: This command is used to create a local copy of a remote repository. You specify the URL of the remote repository, and Git will download all the files and the version control history to your local machine.
    Git clone ‘https code of gtihub“

git add: This command is used to stage changes in the working directory for commit. When you use git add, you are telling Git which changes you want to include in the next commit.
Git add –all= ALL files are added to stage
Git add . = only this directory file changes are added
Git add * =only existing changes are added not deleted ones

git commit: This command is used to save changes to the repository. When you use git commit, you are creating a new revision in the version control history that includes all the changes that you staged using git add.


git status: This command is used to view the status of the current repository. It will show you which files have been modified, which files have been staged, and which files are in the working directory but have not been staged.


git diff: This command is used to view the differences between two revisions of a file or between the working directory and the staged changes.
Git diff = it shows the diff bet current working file and staged file
Git diff –staged = diff between staged and commit changess

git log: This command is used to view the version control history of the repository. It shows a list of all the commits, along with the author, date, and message for each commit.
Git log -p -1= shows last commit
Git log -p -n= shows n commit


git branch: This command is used to manage branches in the repository. A branch is a separate line of development that allows you to make changes to the code without affecting the main branch of the repository.
Git branch- show how many branches are there
Git branch name- creating new branch

git checkout: This command is used to switch between branches or to switch between different revisions of the repository. When you use git checkout, you can quickly move between different versions of the code to compare changes or to revert to an earlier version if necessary.
Git checkout branch_name= go to that branch
Git checkout file_name = the file will be again regained from local repo
Git checkout -f =  all changed file wii be regained form local repo

git merge: This command is used to merge changes from one branch into another branch. When you use git merge, you are integrating the changes from one branch into the branch that you are currently working on.
Git merge branch_name= jar theke notun update nite cai tar nam

Git reset: regain to last phase before the last stage
Git reset –hard= all changes will be gone

touch .gitinore- files included here not be traced

Git rm file_name -f = removed from workplace+git repo

git rebase:






 
