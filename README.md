# GitHub-Commands
Some basic GitHub commands which are used commonly.

Assuming that ssh is set. Refer: https://github.com/C0deBl00ded/Adding-SSH-to-Github

To initialize a repository, Git creates a hidden directory called . git . That directory stores all of the objects and refs that Git uses and creates as a part of your project's history.
> git init

Add all files to staging
> git add .

Commit to staging
> git commit -m "<Type changes for commit>"

Pushing staging code to remote
> git push

Getting new changes from master branch
> git pull

Creating a new branch in local
> git branch <branch name>

Switching into another branch
> git checkout <branch name>
  
Pushing branch remotely
> git push --set-upstream origin <branch name>
  
Creating a new file with some text in it.
> echo "<Type the text>" >> <filename>.txt
  
Merging any local branch in local master branch
> git checkout master

> git merge <branch name>
  
