# LINUX COMMANDS
# 1) Package management (Debian-based)
|command       | Description        |Example                |
|--------------|--------------------|-----------------------|
|'apt update'  | Update repo info   | 'supo apt update'     |
|'apt upgrade' | upgrade packages   | 'sudo apt upgrade'    |
|'apt install' | install a package  | 'sudo apt install nmap'|
|'apt remove'  |remove a package    |'sudo apt remove apache2'|

# 2) File & dictionary commands
| Command | description |Example |
|---------|-------------|--------|
|'pwd'    |show current dictionary| 'pwd'|
|'ls'    |List files/directories | 'ls-l'|
|'ls-l'|Detailed listing |'ls-l'|
|'ls-a'|show hidden files|'ls-a'|
|'cd'|change directory|'cd /etc'|
|'cd ..' |Go up oone level         |'cd ..'                    |
|'cd ~'  |Go to home directory     |'cd ~'                     |
|'cd -'  |Go to previous directory |'cd -'                     |
|'mkdir' |Create directory         |'mkdir testdir'            |
|'rmdir' |Remove empty directory   |'rmdir testdir'            |
|'rm'    |Remove file/directories  |'rm file.txt', 'rm -r dir/'|
|'touch' |Creat empty files        |'touch file.txt'           |
|'cp'    |Copy file/directories    |'cp file1.txt file2.txt'   |
|'mv'    |Move/rename file         |'mv file1.txt file2.txt'   |
|'find'  |Search for files         |'find . name "*.sh"'       |

## 3) File content commands
|Command           |Description                  |Example                         |
|------------------|-----------------------------|--------------------------------|
|'cat'             |View file content            |'cat file.txt'                  |
|'more', 'less'    |View file with scroll        |'more file.txt', 'less file.txt'|
|'head'            |View first 10 lines          |'head file.txt'                 |
|'tail'            |View last 10 lines           |'tail file.txt'                 |
|'wc'              |Word/line count              |'wc -1 file.txt'                |
|'cut'             |Extract column               |'cut -d', '-f file.csv'         |
|'sort'            |Sort file lines              |'sort file.txt'                 |
|'uniq'            |Removes duplicates           |'uniq file.txt'                 |
|'diff'            |Show difference between files|'diff file.txt'                 |
