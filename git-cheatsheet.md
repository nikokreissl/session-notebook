### Git-cheatsheet

_Here are the main commands for git_

##### git init
Opens new local git repository in current folder

**Do not open new repo within a repo!!!**

##### git status
Tells you about the status of the repo 
- untracked: new file which will not be commited and pushed
- tracked: file was added (see below) and would be part of the commit
- modified: file was modified and would need to be added to be part of the commit

##### git log
Shows you the logs of the commits

##### git add filename
Adds a file to be tracked (staging) so it is part of the commit - otherwise will not be tracked

##### git commit -m "commit message"
Adds files and dirs to commit so they would be pushed

##### git restore filename
Restores latest commit of a file

##### git push
Pushes to Github  

**For initial push to Github require `git push add origin` is required**


