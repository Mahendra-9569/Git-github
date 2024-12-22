# Git-github
1->
//Git- is a version control system that helps to track changes in code
//Gitgub - That allows evelopers to store and manage their code using git 

//COFIGURing GIT 

{
    command:
    git config --global user.name "mahendra yadav"
    git config --global user.email"mahendrayadav37104@gmail.com"
    git config --list
}

//CLONE- clone a repository on our local macj=hine git clone <link>
{
    git clone <link>
    git status 
    clear
    cd ..(going outside from any current file/folder)
    cd <file name>  (coming inside any file)
    


}

{
    ls (give any file name)
    ls -a (give all file name)
}


ADD - add new or changed file in your working dictonary to the git staging area
{
 git add <file name>
}

COMMIT - it is the record of change 
{
    git commit -m "record of change"
    git add . (-> for all change at same time )
}

push command -> To upload local repo content to remote repo
{
    git push origin main
}

2-> IF WE CREATE create a file or folder directly local machine and want to push it on remote machine with creating repo on github(first)

{
    cd ..
    mkdir <file name>
    cd <file name>
    git init
    ls 
    ls -a
    git add .
    git commit -m " change"
    git remote add origin <link>
    git remote -v(to verify remote)
    git branch (to check branch)
    git branch -m main (rename branch)
    git push origin main



}


BRANCH command
{
    git branch (to check branch)
    git branch -m main (to remove branch)
    git checkout <branch name>
    git checkout -b <branch name >  (to create new branch )
    git branch -d <branch name>  ( to delete branch)

}

MERGING THE CODE 
{
   
   1->
    git diff < branch name >
    git merge <branch name>


    2->
    create pull requeat
}
