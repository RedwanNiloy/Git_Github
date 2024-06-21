Git: Git is a version control system for managing source code

Github: Github is  a web-based platform that provides hosting for Git repositories. It's a web-based Git repository manager that provides access control, collaboration features, bug tracking, and many other tools for software development
 
Always do - git pull origin master

Working spacel->>staged->Local repo

Ws to staged = add
Stage to local repo = commit
Local to remote = push


git init - This command is used to initialize a new Git repository in the current directory. It creates a hidden .git directory that stores all the version control information for the repository.


git clone: This command is used to create a local copy of a remote repository. You specify the URL of the remote repository, and Git will download all the files and the version control history to your local machine.
    Git clone ‘https code of gtihub“


git add: This command is used to stage changes in the working directory for commit. When you use git add, you are telling Git which changes you want to include in the next commit.

Git add –all= ALL files are added to stage
Git add . = only this directory file changes are added
Git add * =only existing changes are added not deleted ones



git commit: This command is used to save changes to the repository. When you use git commit, you are creating a new revision in the version control history that includes all the changes that you staged using git add.



git status: This command is used to view the status of the current repository. It will show you which files have been modified, which files have been staged, and which files are in the working directory but have not been staged.
Between staged or not staged


git diff: This command is used to view the differences between two revisions of a file or between the working directory and the staged changes.
Git diff = it shows the diff bet current working file and staged file
Git diff –staged = diff between staged and commit changess



git log: This command is used to view the version control history of the repository. It shows a list of all the commits, along with the author, date, and message for each commit.
Git log -p -1= shows last commit
Git log -p -n= shows n commit
Git log - -oneline –graph — ---best



git branch: This command is used to manage branches in the repository. A branch is a separate line of development that allows you to make changes to the code without affecting the main branch of the repository.
Git branch- show how many branches are there
Git branch name- creating new branch


git checkout: This command is used to switch between branches or to switch between different revisions of the repository. When you use git checkout, you can quickly move between different versions of the code to compare changes or to revert to an earlier version if necessary.
Git checkout branch_name= go to that branch
Git checkout file_name = the file will be again regained from local repo
Git checkout -f =  all changed file wii be regained form local repo


git merge: This command is used to merge changes from one branch into another branch. When you use git merge, you are integrating the changes from one branch into the branch that you are currently working on.
Git merge branch_name= jar theke notun update nite cai tar nam
The git push origin main


Git reset: regain to last phase before the last stage
Git reset –hard= all changes will be gone
Git reset comment_id- will reset till commment id
Git reset - -soft/hard/mixed id 
Git reset - -soft/hard/mixed id  Head~n
https://www.atlassian.com/git/tutorials/undoing-changes/git-reset#:~:text=Comparatively%2C%20git%20reset%20%2C%20moves%20both,third%20tree%2C%20the%20Commit%20tree.




touch .gitinore- files included here not be traced

Branch del : git branch -d name

stash :   git stash - save changes in draft || git stash apply— changes in draft applied to workplace

Git log - - online –graph - git log saved tree


Git control:


Git rm file_name -f = removed from (workplace + git repo)



Want to make merge:
Git  pull - it will (fetch + merge) merge with remote creating another tree branch and then merge. It will create non organized version history
Git rebase : 3 ways:
 Git pull - - rebase origin main– it will add my local commit on top of the remote commits and merge it.
Git pull - -ff -only origin main – we will use this whenever there our local branch is behind the main branch and has no additional commit in local repo. (fast forward)




After doing all these things in local machine we have to push it to github so adding/deleting /modifying all things will be done in github





 
