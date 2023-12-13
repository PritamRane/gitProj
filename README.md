# gitProj


1. Initialized Project : 

mkdir gitProj

cd gitProj/


hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /home/pritam/gitProj/.git/


https://github.com/PritamRane/gitProj.git

2. make branches :

git branch feature-branch1

git branch feature-branch2


3. add file to branch :

 git checkout feature-branch1
 touch commit.log
 nano commit.log

4. Merging Branch

git merge main


5. conflict

<<<<<<< feature-branch1
This is feature1 branch
=======
This is feature2 branch
>>>>>>> main


resolved conflict

This is feature2 branch



6. git merge --continue

7. git push
