# trying_git
here's a little repository to try out some git commands  
heres the [cheat sheet](https://training.github.com/downloads/github-git-cheat-sheet/) if you still need it
<br><br>

0. check that your have the right remote repo
> git remote show origin

1. make a new branch called your name and automatically switch to it
> git branch -b [your name]

2. add a file to the directory (folder) you're working in

3. stage your changes (all of them or just the file your edited)
> git add -A <br> git add [file name]

4. commit your changes and add a note
> git commit -m [note]

5. push your branch to the main repo
> git push origin [branch name]

6. if other have already finished and you want to do it you can try pulling from the main branch and see their changes with
> git pull origin
