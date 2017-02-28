1 Create repositories

$ git init [project-name]
Creates a new local repository with the specified name

$ git clone [url]
Downloads a project and its entire version history

2 Making changes

$ git status
Lists all new or modified files to be committed

$ git add [file]
Snapshots the file in preparation for versioning

$ git add *
Adds all changes

$ git reset [file]
Unstages the file, but preserve its contents

$ git diff
Shows file differences not yet staged

$ git diff --staged
Shows file differences between staging and the last file version

$ git commit -m "[descriptive message]"
Records file snapshots permanently in version history

$ git commit -a -m "$1"
Adds and commits all changes with a message

$ git push
Pushes changes

3 Branching and merging

$ git branch
Lists all local branches in the current repository

$ git branch [branch-name]
Creates a new branch

$ git checkout [branch-name]
Switches to the specified branch and updates the working directory

$ git merge [branch]
Combines the specified branch’s history into the current branch

$ git branch -d [branch-name]
Deletes the specified branch
