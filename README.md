# Git_Github_VersionControl
In this quick guide, I'll break down the basics of version control using Git and GitHub, making it easy for beginners and experienced developers alike.


## Setup and Initialization
Command	Description

_**git config --global user.name "[firstname lastname]"**_	Set a name that is identifiable for credit when reviewing version history.

_**git config --global user.email "[valid-email]"**_	      Set an email address that will be  associated with each history marker.

_**git config --global color.ui auto**_	                    Set automatic command line coloring for Git for easy reviewing.

**_git init_**	                                            Initializes a new Git repository.

**_git clone repository_link_**	                            Clones a remote repository to the local machine.


## Basic Commands
Command	Description

_**git status**_                                           Show modified files in working directory, staged for your next commit.

_**git add filename**_                                     Add any particular file only.

_**git add .**_                                            Adds all modified or untracked files to Git.

_**git commit -m "some message"**_	                       Records changes in the local repository.

_**git commit -m "msg1" -m "msg2"**_	                     For multiple line commit message.

_**git commit -a -m "your message"**_	                     Stage any changes to tracked files and commit them in one step.

_**git commit --amend**_	                                 Replaces the previous commit with a new commit that has its own unique identifier and the amended message.


## Branching and Merging
Command	Description

_**git branch**_                                           List branches (the asterisk denotes the current branch).

_**git branch -a**_	                                       List all branches (local and remote).

_**git branch -d branchname**_	                           Delete a branch.

_**git branch -M main**_	                                 Rename a branch.

_**git checkout branchname**_	                             Navigating or moving from one branch to another.

_**git checkout -b new_branchname**_	                     Checkout from a branch and create  new branch simultaneously.

_**git checkout main**_                                    Going from a branch to the main branch in the repo.

_**git merge branchname**_	                               Joins changes from one branch to another.

_**git merge --abort**_	                                   Can only be used after merge conflicts; aborts the merge and goes back to the pre-merge state.

_**git merge source_branch target_branch**_	               Merge source branch into target branch.

_**git stash**_                                            Temporarily shelve or stash current changes.

_**git stash clear**_                                      Remove all stashed entries.


## Remote Operations
Command	Description

_**git push origin branchname**_                           Upload your local branch's changes to a remote repository.

_**git push -u remote branchname**_	                       Sets the upstream reference for the specified branch.

_**git remote**_	                                         Manages remote repositories.

_**git remote -v**_	                                       Lists all remote repositories and their URLs.

_**git remote show name**_	                               Shows info about a single remote repository.

_**git remote update**_	                                   Fetches updates for remotes or remote groups.

_**git remote add origin link**_	                         Adds a remote repository named origin with the specified link URL to your local Git repository.

_**git fetch**_	                                           Retrieves remote updates.

_**git fetch remote_name branchname**_	                   Fetch updates from a specific branch in a remote repository.


## Inspection and Comparison
Command	Description

_**git log**_	                                             To check all the commits in all branches / history of git commits.

_**git log --stat**_	                                     Shows which files were changed, how many lines were added and removed.

_**git log --graph --oneline --all**_	                     Provides a concise and visual representation of your entire commit history across all branches.

_**git log -2**_	                                         Gives details of the last 2 commits.

_**git log --pretty=oneline**_	                           To demo all commits separately in 1 line.

_**git diff branchname**_	                                 To compare commits, branches, files & more.

_**git diff --staged**_	                                   Shows the differences between staged changes and the last commit in Git.

_**git blame filename**_	                                 Determine who last modified each line of that file, and when they made those changes.



