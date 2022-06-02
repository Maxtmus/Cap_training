# Cap_training
The pupose of this workshop is to get familiar with using a GitHub.  
This repository has presentation, which might be usefull before participating in the workshop. Especially if this is the first time you are using version control system.

* [Introduction](#cap_training)
* [Naming conventions](#naming_conventions)
* [Training](#training)
	* [Meeting the requirements](#meeting-the-requirements)
	* [Initialising the repository](#initialising-the-repository)
	* [Commiting the changes](#commiting-the-changes)
	* [Code review](#code-review)
	* [Integration with GitHub Projects](#integration-with-GitHub-Projects)
	* [Feedback](#feedback)
	* [Useful commands](#useful-commands)

## Naming_conventions

### Branch Names
* Use template "feature/\<issueId\>/\<kebab-case-branch-name\>

### Git Commit Messages

* Use template "#\<issueId\> \<message\>"
* Use the present tense ("Add page" not "Added page")
* Use the imperative mood ("Move class to..." not "Moves class to...")
* Length of message should be as short as possible

### Pull Requests
* Use template "#\<issueId\> \<pull request title\>

## Training
###  Meeting the requirements
* Create a github account on: [LINK](https://github.com/)
	* Or use your existing account
	* Or use your Microsoft email account
* Install the Git client to manage repository locally
	* [Git Bash](https://git-scm.com/downloads)
	* [GitHub Desktop Client](https://desktop.github.com/)
	* Remember to change default text editor during instalation
* Create local folder for the purposes of the training
	* Open folder in the Git Bash or open Desktop Client
* Let others know that you finished preparing the environment

###  Initialising the repository
* Clone the repository with the given URL
	* $ git clone <URL>
* Get inside and check for its content
* Pull the newest changes from the remote repository
	* $ git pull
* Create a new branch for yourself with following format:
	* {name}/{issueId}/update-hall-of-fame
	* $ git branch {branch}
* Switch to your new branch
	* $ git checkout {branch}
	* Follow git error message on how to connect to remote branch

###  Commiting the changes
* Open the file with your favoureite text editor
* Add the new line with your name and the date in following format
	* {Name}-{Date}
* Save and close the file
* Go back to application/console
* Add changes to the Staging area
	* $ add {name of the file}
* Check the status and differences
	* $ git status
	* $ git diff
* Commit the staged files
	* $ git commit
	* $ git commit –m „{meaningfull text}”

###  Code review
* Check your remote branches
	* $ git remote -v
* Push your changes to the remote repository
	* $ git push {remote} {branch}
* Go to the GitHub page and log into training repository
* Switch to your branch and create a Pull Request
	* Add someone as a reviewer
* DO NOT MERGE untill your review is accepted
* Make requested changes and resolve any conflicts
	* This means use GitHub, or your local repository to adjust the code, so the changes can be automaticaly merged by git
* IF ACCEPTED - MERGE

###  Integration with GitHub Projects

###  Feedback

## Useful commands
* Git cheat-sheet from Tower. Set of basic commands and a bit of theory. [LINK](https://www.git-tower.com/blog/git-cheat-sheet/)
* Git cheat-sheet from GitHub. Simple sheet with commands. [LINK](https://education.github.com/git-cheat-sheet-education.pdf)
* Check the presentation
