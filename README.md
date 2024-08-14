# Git_Project
learn git how to push, pull, commit, merge and rebase

<<<<<<<<<<<git commands
git
git init--initaliaze empty git
git add, git commit, git push
la -la  -- hidden file
ls .git
git status  -- track of version of file
git add cal.sh
vim cal.sh -- make changes
git status -- tell the changes had done
git diff -- what changes done
vim cal.sh -- make changes
git diff cal.sh
git add cal.sh
git commit -m "1st version change"
git restore cal.sh
git status
git restore cal.sh --discard changes
vim cal.sh --make changes
git diff cal.sh
git add cal.sh
git commit -m "2nd version change"
git log  --   what are the commits it shows
(copy the log previous id for previous changes 3b5dafe0ba6a17e51f36de9a4ed90d22b35c35ac)
git reset --hard 3b5dafe0ba6a17e51f36de9a4ed90d22b35c35ac    (precious changes version)
cat cal.sh  --we can check the previous changes
GitHub or Self Hosred Git or Bitbucket

types of branches
1)master branches
2)Feature branches
3)Release branches
4)hotfix or bugfix branches

ls init
ls -a
ls .git/hooks/pre-commit.sample
git status
vim cal.sh
git diff 
git status
git add cal.sh -- any changes or add file and to track
git checkout cal
git add .
git commit -m "my 1st commit
git log
git push -- push to github in repository for everyone access
git add &&  git commit -m "" && git push
git clone giturl -- to dowload local
git clone https://github.com/bollarapusrinivasraju/snake_game_project.git
git remote -v --remote reference
git remote add "bollarapusrinivasraju"
cd snake_game_project
ssh-keygen -t rsa  --generate public key
vim /users/projects/git.ssh
cd /users/projects/git.ssh
--copy ssh key from .ssh file in git hub setting ssh
 diff clonee vs fork
clone means download
fork is used to create a copy of repository

####
git add cal.sh
ls
rm -r project_snake_game --deleted the dir
git diff
git add .
git commit -m "THis is 1st commit"
git log
git branch --create a branch
git checkout -b division   --create a new branch and switch to the new branch


vim cal.sh
git add cal.sh
git commit -m "added div fun."
git log
git checkout master   --change to main branch
-------using branch option we can do seprate add function

####merge branch ####
git merge, git rebase git cherry-pick   --3 merge process


git log divison --change to divison branch
git checkput division && git log --change to divison branch

git cherr
git log

#copyting the branch from division branch to master branch
git log division
---copy the commit id  1aa0dce0e2a528d4411152e09be8684f87c2f282
git cherry-pick 1aa0dce0e2a528d4411152e09be8684f87c2f282
git log -- u can  see the changes of merge


#diff git rebase and git 
git checkout -b mergeexm
vim cal.sh   # add func mul
git add cal.sh
git commit -m "done "
git checkout master
git checkout -b 'rebase_example'
vim cal.sh   # add func mul
git add cal.sh
git commit -m "percentage"
git log --oneline
git checkout main

git merge mergexm
git status
git commit -m "add changes"
git rebase rebaseexample
git rebase -continue


main -merge exmple - merge example
rebase example - percentage
added new functioality
test commit
git merge vs git base
