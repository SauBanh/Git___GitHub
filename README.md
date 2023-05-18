# Git___GitHub
## Learn how to use Windows Command Port
1. cd:
  * "cd ..": return to the parent directory of the current directory
  * "cd <name folder in the current directory>": Move to folder <NAME FOLDER>
  * "cd path": move to the path
  * "cd /": back to the root directory
2. dir:
  * "dir": show all folders and files contained in the current directory
  * "mkdir <NAME FOLDER>": create a new folder with the name <NAME FOLDER>
3. echo
  * "echo <NAME FILE>": create a new file with name <NAME FILE>
  * "echo <CONTENT> <NAME FILE>": create a new file with the name <NAME FOLDER> and the content inside the file is <CONTENT>
4. del:
  * "del <FILE NAME>": delete <FILE NAME> present in current directory
  * "mrdir <FOLDER NAME>": delete <FOLDER NAME>
5. copy:
  * "copy <FILE> <FOLDER>": copy <FILE> to <FLODER>
6. move:
  * "move <FILE/FOLDER> <FOLDER>": move <FILE/FOLDER> to <FOLDER>
7. cls:
  * "cls": delete all commands just typed on terminal
## How does work - Simplified!
 ![image](https://github.com/SauBanh/Git___GitHub/assets/69725247/5524fe88-e7a4-4b45-971d-776418eae83b)
 ![image](https://github.com/SauBanh/Git___GitHub/assets/69725247/b1378fcd-3627-4d4e-ba16-b861d1c9d51c)
![image](https://github.com/SauBanh/Git___GitHub/assets/69725247/22d5da47-e93d-428a-b088-5cf5f50fde20)
![image](https://github.com/SauBanh/Git___GitHub/assets/69725247/1cefc3aa-3bd4-49d0-9c3b-5c722a1365b4)
![image](https://github.com/SauBanh/Git___GitHub/assets/69725247/dfa0627e-fe29-4f21-8bd7-2bee85f2231e)
### Branches
 ![image](https://github.com/SauBanh/Git___GitHub/assets/69725247/81a8d0ad-4f49-4b36-993b-eaf03a3e1047)
![image](https://github.com/SauBanh/Git___GitHub/assets/69725247/022ecaea-69e8-4063-8a0f-719063a11696)
![image](https://github.com/SauBanh/Git___GitHub/assets/69725247/bae1275b-7a6d-4029-988f-a2f5e32c1768)
 ### command git
 * "git init": Initializing the Repository
 * "git status": current state of the repository
 * "git commit -m"commit some thing you do it": 
 * "git log": show all action you do, To exit this menu, please press "q" and confirm this with Enter on your keyboard.
 * "git branch": Check which branch is currently on and show all existing branches at the same time
 * "git branch <name branch>": create new branch with name <name branch>
 * "git checkout branch": if the branch does not exist, it will create <name branch> and move to <name branch>, if it does, it will move to the branch <name branch>
 * "git checkout -b branch": if the branch does not exist, it will create <name branch> and move to <name branch>, if it does, it will move to the branch <name branch>
 * "git merge": important! you must be on the branch you want to merge into . For example, if we want to merge B into A, we have to be on branch B and type the command git merge <branch to merge>
 * "git checkout <id in git log>": go to the moment of the state <id in git log>
 * "git switch <name branch>": switch <name branch>
 * "git switch -c <name branch>": create new branch with name branch <name branch> and go to new branch
 * "git ls-file": go to the moment of the state
 * "git rm <name files>": delete files <name files> in repo
 * "git checkout <name file>": will check status <name file>
 * "git checkout .": check all status file
 * "git restore <name file>": return to the previous state of that file
 * "git clean -dn": select the files to delete, the file has not been added to the repo
 * "git clean -df": delete the files checked in the command "git clean -dn"
 * "git reset <file name>": select <file name> to change to the previous state. If the file is committed, it will return to the uncommitted state, and if you retype this command, it will return to the commit state
 * "git reset --soft HEAD~1": delete commit
 * "git branch -D <name branch>": delete branch have name <name branch>
 * "git branch -D <name branch> <name branch>": delete 2 file
 ### .gitignore
 in file log i write 
 * test.log. file test.log won't add to repo
 * .log : .log files will not be added to the repo
 * web-app/*: the web-app directory will not save to the repo along with all the files in that directory nor will it save to the repo
