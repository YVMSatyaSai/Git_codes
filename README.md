                   GIT DELETE BRANCH

git branch --all

for all including remote and local

git switch - 

goto previous branch

git branch -d BRANCH_NAME
git branch --delete BRANCH_NAME

to delete the branch from local repository

         GIT BRANCH PUSHING TO REMOTE REPOSITORY

git push origin NEW_BRANCH_NAME

            GIT BRANCH HOW IT WORKS

snapshots
hexadecimalvalue
checksum
pointer

git log --graph

Git Graph --> download the extention in vscode.

                 GIT MERGE



first swith to the main branch

git switch main

now pull the code from the remote repository

git pull origin main

it is good practice it will take all the latest data from remote git repository

second merge the new branch with main

git merge NEW_BRANCH_NAME

now push it to the remote repository

git push origin main

                 GIT REBASE

git add .

git rebase NEW_BRANCH_NAME

while merging to maintain all in the one line on graph

                   GIT MERGE CONFLICT

git config pull.rebase false
git pull origin main
   
                    GIT TIME TRAVEL

 git checkout COMMIT_CODE

by doing this head was detached from the last commit and jumps to the commit_code step.

git checkout -b lite-version

by this command we are re-attaching the code to the new branch.
If u want u can also us existing branch as well.

git add .
git commit -m "committing the liteversion"
git push origin lite-version

                GIT STASH

git stash

git stash list

git stash apply 

git switch main

                 GIT FORK

the modifications which you can do in your own repository. by getting the code from some where others remote repositories.

All done in github ui

                 GIT PULL REQUEST


your cloning the code from others repository by fork future and making the changes in your own remote repository and then creating a pull request to the user from where you have cloned earlier for the sake of change need to happen for every one 

now this request is verified by the main user in the github pull request tab and checking the chages and now his wish weither he need to accept or reject.

once he accepted it will visible for all user.

            


