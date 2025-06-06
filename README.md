# Git-github
1->
<br>
//Git- is a version control system that helps to track changes in code
<br>
//Gitgub - That allows evelopers to store and manage their code using git 
<br>

//COFIGURing GIT 
<br>

{
<br>
    command:
    <br>
    git config --global user.name "mahendra yadav"
    <br>
    git config --global user.email"mahendrayadav37104@gmail.com"
    <br>
    git config --list
    <br>
}
<br>

//CLONE- clone a repository on our local machine git clone <link>
<br>
{
<br>
    git clone <link>
    <br>
    git status 
    <br>
    clear
    <br>
    cd ..(going outside from any current file/folder)
    <br>
    cd <file name>  (coming inside any file)
    <br>
    


}
<br>

{
<br>
    ls (give any file name)
    <br>
    ls -a (give all file name)
    <br>
}
<br>


ADD - add new or changed file in your working dictonary to the git staging area
<br>
{
<br>
 git add <file name>
 <br>
}
<br>
COMMIT - it is the record of change
<br>
{
<br>
    git commit -m "record of change"
    <br>
    git add . (-> for all change at same time )
    <br>
}
<br>
push command -> To upload local repo content to remote repo
<br>
{
<br>
    git push origin main
    <br>
}
<br>

2-> IF WE CREATE create a file or folder directly local machine and want to push it on remote machine with creating repo on github(first)
<br>
{
    cd ..
    <br>
    mkdir <file name>
    <br>
    cd <file name>
    <br>
    git init
    <br>
    ls 
    <br>
    ls -a
    <br>
    git add .
    <br>
    git commit -m " change"
    <br>
    git remote add origin <link>
    <br>
    git remote -v(to verify remote)
    <br>
    git branch (to check branch)
    <br>
    git branch -m main (rename branch)
    <br>
    git push origin main
    <br>



}
<br>


BRANCH command
<br>
{
<br>
    git branch (to check branch)
    <br>
    git branch -m main (to remove branch)
    <br>
    
    git checkout <branch name>
    <br>
    git checkout -b <branch name >  (to create new branch )
    <br>
    git branch -d <branch name>  ( to delete branch)
    <br>
    }

MERGING THE CODE 
<br>
{
<br>
   
   1->
   <br>
    git diff < branch name >
    <br>
    git merge <branch name>
    <br>


    2->
    <br>
    create pull requeat
    <br>
}
