# Branch Commands

`git branch *branch_name* - command to create a branch`

`git checkout *branch_name* - command to change the HEAD to the branch`

You can change the HEAD to the master writing `git checkout master`

`git merge *branch_name* - this do the merge of the *branch_name* to the current branch or master`

`git branch - d *branch_name* -  this delete the branch *name_branch*`

`git branch -  show the master and all the branches`

`git checkout -b *branch_name* - create a branch and switch to the branch`

`git rebase master -  this to the reabse to the master`

Note - after rebase you have to do checkout and merge commands

`git reset *commit_hash* --hard - this put HEAD in the *commit_hash* commit`

`git rebase -i master - shows a editable list of the commits to be rebase into master`
