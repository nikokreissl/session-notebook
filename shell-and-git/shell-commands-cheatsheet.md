## Shell commands Overview

##### pwd (print working directory)

Shows in which directory you are currently

##### cd (change directory)

Allows you to move around in directories

- "cd .." moves to the parent directory. With each additional "." you are moving one more dir up
- "cd <dir>" moves you to the desired directory. You can move through several dirs at a time by listing the elements "cd <dir/sub-dir/sub-sub-dir>"

##### ls (list)

Shows the sub-dirs and files of the directory

- "ls -l" shows the files and subdirs in a list
- "ls -a" shows hidden files and subdirs in the currenty directory
- "ls -al" shows as list with hidden files and subdirs

##### mkdir <dir> (make directory)

Creates a new directory with the given name

##### touch <file>

Creates new file in the current dir

##### code . / <file>

"code ." opens current dir in VCS, "code <file>" creates new file in current dir and opens in VCS

##### mv

Allows you to rename and/or move a file

- `mv <file> dir/sub-dir` moves file into a new dir
- `mv <file> <new-file-name>` changes the name of the file

##### open <./file>

Opens current dir or the desired file in Finder

##### rm <file/dir>

Deletes file or dir, will ask for confirmation

##### echo <file> "message"

Adds text to a file

##### cat <file>

Shows content of a file
