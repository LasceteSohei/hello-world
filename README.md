# HowToGit : My little remainder of how to use git command line #

## Initializing git project repository  ## 
	' git init ' + repository path

## See the status of the current git project repository ##
	' git status '

## Add to git project repository  ##
	' git add <pathtofile> '

## Committing a file ##
	' git commit <filetocommit> '

## Get differences between new and old version (when old version commited) ##
	' git diff <file> '

## Change history ##
	' git log '

	' q ' to exit

## Moving to a branch ##
	' git checkout <nameofbranch> '

## Creating a branch ##
	' git checkout -b <nameofbranch> '

## Deleting a branch ##
### Local ###
	' git branch -d <nameofbranch> '
### Remote ###
	'git push origin --delete <nameofbranch> '

## Showing all the branches ##
	' git branch -a '

## Merging two branches ##
	' git merge <nameofdaughterbranch> '

## Pushing to github ##
	' git push '

## Changing the editor used for commit messages  ##
	' git config --global core.editor <appName> '

## Setting the name ##
	' git config --global user.name <name> '

## Setting the email ##
	' git config --global user.emai <email> '

