
$ git --version
git version 2.14.1.windows.1

$ git config --global user.name "areszn"

$ git config --global user.email "areszn1988@gmail.com"

$ pwd
/c/Users/Administrator


$ cd e:

$ pwd
/e

$ cd Projects/
$ mkdir Git
$ cd Git/
$ mkdir gittest
$ cd gittest
$  pwd
/e/Projects/Git/gittest
$ cd -
/e/Projects/Git


$ git init

$ git add readme.txt
$ git commit -m "1st test git"
$ git status
$ git diff
$ git status
$ git log
$ git log readme.txt
$ git reset --hard HEAD^
$ git reset --hard HEAD~1
$ git reset --hard c12a44bc08a980322b5b2be96711103c6c490349
$ git log
$ git reflog
$ git checkout -- readme.txt




$ ssh-keygen -t rsa -C "areszn1988@gmail.com"



$ git config -l




$ git remote add origin git@github.com:areszn/learngit.git
$ git push -u origin master
