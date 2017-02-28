1 Create repositories

$ git init [project-name]
Creates a new local repository with the specified name

$ git clone [url]
Downloads a project and its entire version history

2 Make changes

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
