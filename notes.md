## Understanding how to write in md 
super script3<sup>2
subscript 3<sub>2
> quoting code
use back ticks to call out code `git status`
```
hi
```
##demonstration
##git
The .git directory is where all of the versions get stored. 
- to begin tracking version you need to add it `git add .`
-don't need to add again if you use git commit -am
-git checkout beginning has changes it to head
- to get back to top use `git checkout master`
- git diff HEAD HEAD~1 - numerical distanec away from head
-use git branch as and start working on it with git checkout A
- combine by checking out master and executing git merge A
- every time you commit you store a copy of that file 
- git init or create repository in github
- git push pushes changse up
- git pull commits down
- git fetch tells you the latest info about changes on Github
- git status tells you the differences between the clones

#Forks
- fork clones to github instead of ide
- gets you a copy of open source code you want to experiment
- pull request; you change it up and tell the originator if they want your changes