# Remote repository commands

Here you can find commands that can help with remotes repositories.

To clone a repository using ssh you should see this github help.
[About SSH](https://help.github.com/articles/about-ssh/)

`git clone *ssh_key*`

Or you can clone by the html

`git clone *url_copied*`

`git remote add origin *ssh_key*`

`git pull origin`

`git push -u origin master`

`git push origin -d *branch name* - put the branch direct to master`

`git push -u origin *branch_name* - put the local branch changes to the remote branch repository`

`git fetch --all - put in all new branches`

`git fetch --all --prune - delete branches after merge with master`

The two following commands are the same of git pull origin

`git fetch origin`

`git merge origin/master`
