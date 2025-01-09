# Remotes

## Git Remote Repositories ##
Remote repositories are essential for teamwork. A git remote repository is an instance of the project repository hosted on the internet or other network.

## Git Remote Commands

### Fetch ###
`git fetch` can be used to download the latest commits from the remote without merging them. Without fetching the latest from the remote `git status` will report "Your branch is up to date with 'origin/main'.

### Pull ###
`git pull` is a combination of the `git fetch` and `git merge` commands. It fetches any commits from the remote and merges them with the local repository.
