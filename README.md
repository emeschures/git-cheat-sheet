# Git Cheat Sheet

### Create Respositories
##### Start a new repo or obtain one from an existing URL

`$ git init [project-name]`: Creates a new local repo with the specified name.

`git clone [url]`: Downloads a project and its entire version history.

### Make Changes
##### Review edits and craft a commit transaction

`git status`: Lists all new or modified files to be committed.

`git diff`: Shows files differences not yet staged.

`git add [file]`: Snapshots the file in preparation for versioning

`git diff --staged`: Shows file differences between staging and the last file version.


`git reset [file]`: Unstages the file, but preserves its contents.

`git commit -m "[descriptive message]"`: Records file snapshots permanently in version history.

### Group Changes
##### Name a series of commits and combine completed efforts

`git branch`: Lists all local branches in the current repo.

`git branch [branch-name`: Creates a new branch.

`git checkout [branch-name]`: Switches to the specified branch and updates working directory.

`git merge [branch-name]`: Combines the specified branch's history into the current branch.

`git branch -d [branch-name]`: Deletes the specified branch.


### Redo Commits
##### Erase mistakes and craft replacement history

`git reset [commit]`: Undoes all commits after [commit], preserving changes locally.

`git reset --hard [commit]`: Discards all history and changes back to the specified commit.

### Synchronize Changes
##### Register a remote (URL) and exchange repo history

`git fetch [remote]`: Downloads all history from the remote repo.

`git merge [remote]/[branch]`: Combines the remote branch into the current local branch.

`git push [remote] [branch]`: Uploads all local branch commits to GitHub.

`git pull`: Downloads bookmark history and incorporates changes.
