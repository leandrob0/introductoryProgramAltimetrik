### Version control systems.

The version control is a way of managing, controlling and tracking the changes made to a software. These systems follow every change made to the software code. Version control systems allows reversing changes (if it had an error for example) and working in groups is made a lot easier.

## Benefits of using a VCS: 
* A complete history of every change made to the software.
* Independent streams of work with branching and merging (multiple developers can work on different things at the same time and even in the same file).
* Complete traceability of the software changes.


## What is git?
Git is the most widely used VCS in the world, in fact, it is a DVCS (Distributed Version Control System) meaning that every developer gets their own complete local repository.

**A git repository is a virtual storage of a project, and GitHub is a Git repository hosting service**, meaning it allows you to track and share your projects outside your computer/server. GitHub is exclusively cloud based. 

One of git main benefit are branches, these allow independence when working on the same software, when starting a new repository, all the changes will be committed to the main branch, but creating other branches makes developing different parts at the same time easier, and you can merge your new branch with its commits to the main branch and not affect the workflow.

## The most common Git commands are: 
* Git init: This turns an empty folder to a git repository.
* Git add: Turns unstaged or untracked files to staged. This means that files that are modified or created, will be added to git, because if this command is not executed, the file update or the file itself will live only in our hard drive. 
* Git commit: Records the changes made to a file to your local repository. For each commit, there is a unique ID.
* Git status: Shows the current state of the repository (unstaged or staged files, committed or not committed files, etc.)
* Git branch: To see which branch are you on, create, or delete a branch.
* Git checkout: To change branches.
* Git merge: To integrate branches together.
* Git clone: To create a local repository from an existing remote one.
* Git push: Sends the local repository changes to the remote one.
* Git pull: Gets the changes from the remote repository for the local repository. It executes first a git fetch to bring the changes, and a git merge later to combine them with your local repository.
* Git tag: Mark a specific point in a repository history as important, typically used to mark new versions of a software.
* Git stash: Saves your changes temporarily so you work on another thing without having to commit unfinished changes.

Git also has git hooks, which are automatized ways of operating with git. Meaning that we can make a script of things to-do after or before a git command. There is a folder that gets created every time you initialize a git repository called hooks inside .git folder. There are predefined hooks, and you need to activate them to use them. You can make things as not allowing a commit unless it has more than 4 characters and less than 30 characters message.

### Git branches and flow.

One of git main benefit are branches, these allow independence when working on the same software, when starting a new repository, all the changes will be committed to the main branch, but creating other branches makes developing different parts at the same time easier, and you can merge your new branch with its commits to the main branch and not affect the workflow.

Basically, a git flow has these branches: 
* Feature branch: Where developers develop features.
* Develop branch: Where developed features get collected.
* Release branch: Branch responsible for version release.
* Hotfix branch: Where online defects get corrected.
* Main branch: Where the baseline of the latest released version gets stored.

Image illustrating this flow from [this post](https://nvie.com/posts/a-successful-git-branching-model/): 
<img src="git-model@2x.png">

### Resources: 
https://www.atlassian.com/es/git/tutorials/what-is-version-control
https://devmountain.com/blog/git-vs-github-whats-the-difference/#:~:text=GitHub%E2%80%A6-what's%20the%20difference%3F,help%20you%20better%20manage%20them.
https://www.freecodecamp.org/espanol/news/git-stash-explicado/
http://guides.beanstalkapp.com/version-control/common-git-commands.html
https://losapuntesdemajo.vercel.app/
https://www.hostinger.com.ar/tutoriales/como-usar-git-hooks#%C2%BFQue_son_los_Git_Hooks
https://victorhckinthefreeworld.com/2022/02/08/con-git-hooks-puedes-automatizar-tareas-al-trabajar-con-git/
https://nvie.com/posts/a-successful-git-branching-model/
https://quangnguyennd.medium.com/git-flow-vs-github-flow-620c922b2cbd#:~:text=Unlike%20Git%2DFlow%2C%20GitHub%2D,processing%20methods%20should%20be%20similar
https://learngitbranching.js.org/?locale=es_ES

