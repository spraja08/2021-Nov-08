2021-Nov-08

- 'git init` : ceate a git repo in the current folder
	- only need to do this once, do not nest repos
- `git status` : Tells the status of the repository

- `git add <FILE>` : adds the file to the staging area
- `git commit` : opens up the configured text editor to type the message
- `git commit -m "<message>"` : commits with the given message 

- `HEAD' : Latest in the history (what you are currently looking at)

- `git diff` : shows the difference from all your files to the last commit
	- `git diff HEAD <FILE>` : only diff the file <FILE>
	- `git diff HEAD~2 <FILE> : diff current state from 2 commits ago
	- `git diff <HASH>` : Diff curremnt state from HASH Location

- 'git log` : looks at your history log
	- 1git log --oneline` : shows the summary of the commits

- `git checkout <HASH> <FILE>` - revert file to the version in the HASH.
- `git status` : read what git status tells you to revert a file and/or unstage the file
- `git restore ...' : to restore
- `git checkout <HASH>` : to move all tje files to their versions in <HASH>
	- `git checkout main` : to back to main branch
	- `git switch main`, `git checkout master` : might do the same thing.
