# Basic Commands

Here we can see the basic commands on github.

`git init - initialize a repository.`

`cat .git/config - shows the information in the file config about your repository.`

`git status - shows the current status of the repository.`

`git config user.name "*user_name*" - save your name for the current repository`

`git config user.email "*user_email*" - save your email for the current repository`

For just save your name and email for all repositories, you can do:

`git config --global user.name "*user_name*"`

`git config --global user.email "*user_email*"`

`git add . - add the changes to the track stage, that means that you are ready for commit.`

`git commit -m "*commit_name*" - just commit all of the add changes.`

`git mv *name_file* *new_name_file* - this will rename the file`

`git rm *name_file* - will delete the file`

`touch *name_file* - create a empty file`

`git diff --staged - you can see the changes in the added files before commit them.`

You can see each commit chages using the hash code in the place of the flag --staged. Anothes flags can be used like HEAD^ and *hash_code^* or *hash_code..hash_code*

`git commit --amend - change the commit message with vi, and you can use to update the commit with new changes`

To edit in vi, use the i key to start editing, and esc and enter, :wq to quit.

To change the editor you can use

`git config core.editor "name_editor --wait"`
