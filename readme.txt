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



