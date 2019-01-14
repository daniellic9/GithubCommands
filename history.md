# History of the Project

Here we can find some commands that can help with the history of the project.

`git log - with this command you can see the commit history of the project`

If the window its too short you can navigate with the up and down arrow, and space to the next page and b to the before page. You can search by /*key_word*, and quit with q.

`git config core.pager cat - you always show all commits, and you don't need the navigate commands for the current repository`

`git config core.pager less - you can show the navigate mode when the window is too short`

`git log -*number* - you will show the last *number* commits`

`git log --oneline - shows all commits with just the hash and the name, one in each line`

You can combine the flags --oneline with -*number* to show the last *number* commits in one line.

`git log --before="*date*" - shows the commits before the *date*`

The date format is yyyy-mm-dd, you can use the flags --after and --since. You can put the hour too, hour format is Thh:mm:ss-*fuse*.

You can use natural language like *2 days ago,* *1 week ago*. And you use the flag --author to search by the author of the commit.
Others flags can be found typing `git help log`.

`git checkout *hash_code* - you can see how the code base was like in the commit of the *hash_code*`

`git checkout master -  you return to the current state of the repository`

`git tag version-*version_number* - create a tag of version in the commit history`

`git tag - shows the list of tags created`

You can do git checkout with the version tag 
