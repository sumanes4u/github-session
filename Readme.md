#GIT COMMANDS




git config --global user.name sumanes4u
git  config --global user.email sumanes4u@yahoo.co.in

//To get branches list
git branch --list
//To switch to test1 branch
Git checkout test1

Git init
Git add readme. Or  git add -A OR git add .
Git commit -m 'messge for commit'
Git remote add origin https://github.com/sumanes4u/farud_detection.git //to form link between local repo and  and git remote repo.
Git push -u origin master

//To check the git previos commits
$ git log --oneline
2bfadb5 (HEAD -> main, origin/main, origin/HEAD) Python sample
a4475b3changes from local
97b28bccommit changes



git remote set-url origin git://new.url.here

//Gives branch name
git branch

//To change the branch name
Git branch -M main

https://sumanes4u.github.io/git-commands/

Be on workingdir and git init 
//git init

//git status

//git add <filename>

//git add -A
All untracked filed to staging area

//git commit -m <message>

//git log --oneline


//git revert HEAD

//git reset --soft <commit ID>

//git reset --hard <commit ID>


//git reset --soft
which will keep your files, and stage all changes back automatically. 

//git reset --hard
 which will completely destroy any changes and remove them from the local directory. Only use this if you know what you’re doing.

Create a new branch
//git checkout -b <dev-branch>

To switch to master branch
//git checkout master

Stay in master branch 
Here dev branches gets merged to master branch
//git merge dev


GIT and GITHUB

//generate SSH keys using 
ssh-keygen

//copy the the public KEY and add into GITHUB
Cat /Users/samarthi/.ssh/id_rsa.pub

GITHUB->setting-> NEW ssh keys

//Local machine perform 
ssh -T git@github.com 



//git push origin
