# Life-with-a-backpack
A travel blog by Ankur Biswas

/// Git Steps
1) Create repository in github
2) Create a workspace in your local machine where you want to keep your local repository
3) git init (it will create a local git repository in your local machine)
4) git remote add origin "https://github.com/Lucifer1990/Life-with-a-backpack.git"  (this will sync your local git repository with remote repository)
5) git pull origin master (this will pull all files from master which is nothing but your remote repo)
6) git status (this will show modified or unindexed files in local git repo )
7) git add -A (this will make all available files indexed )
8) git commit -a -m "your comment" (this will commit changes to your local git repo, -a is to indicate all files, -m to indicate commit message)
9) git branch branchname (will create a new branch which will be having all currently avilable files in master )
10) git checkout branchname (o switch between brances)
11) git merge brachname (to merge changes done in new branch to master. remeber you have to be checked into master branch while doing this step)
12) git config --global user.email iamankurb@gmail.com (need to config user email)
13) git config --global user.name Lucifer1990 (need to config user name)
14) git push --set-upstream origin master (to push everything from local repo to remote repo for the first time. next time onwards only git push)

