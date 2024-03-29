# Note on how to get this assigment

This is how I complete this assignment. The instrustion state that I need to implement an existing repository that capture all the concept of git. 

The repo that I used: [rosboard](https://github.com/dheera/rosboard.git) 


## Create two README.md file
I created two README.md files. One is called README.md that contains this explanation, and the README2.md for the readme file of the repo
I use touch <file name> to create the file and then use command "code ." to open vscode and of the folder to add the content in the file. Then I git add and git commit the files. 

## Commit and create 4 branches for all the four folder 
I created branches by git branch b1, b2, b3, b4

## Add all files in branch 1 in 
I go to branch by : git checkout b1, and copy and paste the folder into the folder and then git add, git commit

## Add all files in branch 2 in
I go to branch by : git checkout b2, and copy and paste the folder into the folder and then git add, git commit

## Add all files in branch 3 in
I go to branch by : git checkout b3, and copy and paste the folder into the folder and then git add, git commit

## Add all files in  branch 4 in
I go to branch by : git checkout b4, and copy and paste the folder into the folder and then git add, git commit

## Add all files in master in
I go to branch by : git checkout master, and copy and paste the folder into the folder and then git add, git commit

## Merge all the branch
I merge branch with master by checkout master and : git merge b1, b2, b3, b4. 

## Write instruction in 
I started writing how I did this assignment in the file 

## Delete README2.md 
After git add and commit new changes, I delete the README2.md file and move on to the next step.

## Push to a github repo
Pusing require setting up SSH and add remote access. 
I used -- ssh-keygen -t rsa -b 4096 -C "6022020007@camtech.edu.kh" -- to create the key and then copy the key into the setting in gitup for authentication. 

I used git remote origin SSH of the repo for setting the remote and the git push -u origin master to push the master into the repo

## Submit 
After everthing have been finalized and adjusted, I submit the assignment. 

