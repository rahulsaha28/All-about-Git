# All-about-Git
This is the git version control system

--------------------------
GIT

--------------------------

1. commit
2. push
3. pull
4. status
5. add
6. diff
7. log
8. show
9. reset (delete commit)
10. branch
11. checkout
12. merge
13. stash (delete git)

## Workflow
 |  State  | command| |
 |-----|-----|----|
 |  start   | git init||
 | show commit and untracked file | git status |
 | add a file to git  | git `<filename>` |
 | locally change track  | git commit -m "Want to write" |
|show what change in file| git diff |
|commit all the file | git commit -am "commit"|
|show all happening in using git | git log|
|show a specific log | git show log_tag|
|how to edit my commit|git checkout log_tag|
|how to cancel the edit commit | git checkout master |
|add something in a commit not edit it | git add `<filename which is add>` , git commit --amend |
|temporary save something | git stash |
|add temporary in it position | git stash pop |
|show all temporary file | git stash list |
|add temporary in it position | git stash pop stash@{1} |
|delete all temporary | git stash clear|
|add remote in github | git remote add `<remote name>` `<github link>`|
|push all in the github repositories| git push origin master |
|pulling data from server | git pull origin master |
|the file which is not in the git push | create .gitignore file|

###Git Repositories: 
Git repositories are folder where git present.
>> git repositories host in a server is called remote


### Git global Setup
>> git config --global user.name "Name"

>> git config --global user.email "gmail"



