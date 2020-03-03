git config --list 


    /*       /home cd /home/awsaf/git-workspace  Initialize git folder     */
➜  git-workspace cd git-test
➜  git-test git init   
Initialized empty Git repository in /home/awsaf/git-workspace/git-test/.git/


/ *  find the status of files committed or not */
➜  git-test git:(master) ✗ git status


/ *  add all new files to git repository */
➜  git-test git:(master) ✗ git add .


/ *  commit the changes to git repository  with message */
➜  git-test git:(master) ✗ git commit -m "1st commit"


/ *  check commit messages */
➜  git-test git:(master) git log --oneline


/ * check the file from an older commit */
➜  git-test git:(14b362d) git checkout 14b362d readme.txt
➜  git-test git:(14b362d) git checkout master
Switched to branch 'master'
➜  git-test git:(master) 
You can also use 'git reset' to reset the staging area to the last commit without disturbing the working directory


/ * push local repository to git online  */
create online repository and then
➜  git-test git:(master) git remote add origin https://github.com/awsafambar/git-test.git
➜  git-test git:(master) ✗ git push -u origin master
Username for 'https://github.com': awsafambar
Password for 'https://awsafambar@github.com': 
Counting objects: 12, done.

/ * Cloning an online repository         */
create a folder and then 
➜  git-test git:(master) git clone https://github.com/awsafambar/git-test.git


