*config*
git config --add --global user.name "deb0pam"
git config --add --global user.email "debopamdas8@gmail.com"
git config --global init.defaultBranch main 

git status shows the status of the directory
git add . adds all the latest changes to the git
git commit -m helps to commit a message
git log --oneline shows the log of the git in one line
git --no-pager log -n 10 --oneline --parents --graph shows everything very nicely
git --unset <key> unsets the key

git branch -m oldbranchname newbranchname changes the branch name
git merge branchname merges the branch to main branch
git branch branchname switches to that branch
git switch -c branchname also does the same
git branch -d branchname deletes the branch
git rebase branchname rebase the commit
git reset commithash used to undo the changes
        --soft undoes the changes but keeps the changes
        --hard undoes the changes by deleting the changes permanently
                HEAD~n goes back the numner of commits backwards

git remote add <name> <uri> creates a copy of the repo
git fetch brings in all the changes of the repo
git merge <reponame>/<branchname> this how you merge the commit if you have two or more remote repo together
curl -sS https://webi.sh/gh | sh for accessing github through terminal

