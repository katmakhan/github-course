# Github Guide for Dummies
This contains all the necessary CMD line commands to execute and add new repositories in github. This will include adding new project, changing user name, global initialization of usernames. 


## Follow these methods to get started

- Git ORIGIN 
	```console
	git add remote origin <github-url>
	```
	```console
	git remote rm origin
	```
	```console
	git remote -v - To view the origin
	```
	Renaming the origin 
	```console
	git remote set-url origin <new-url>
	```

- GIT PROCEDURE:
	To add new files and updating the commits in the github
	```console
	git add .
	```
	```console
	git commit -m "init"
	```
	```console
	git push origin master
	```

- Viewing GIT
	To view the git user and email credentials
	```console
	git config --global --list
	```
	```console
	git config credential.username
	```
	```console
	git config user.name
	```
	```console
	git config user.email
	```


- TODO:
	If you want to change the username and user email for the individual project

	```console
	git config user.name "<if name with spaces>"
	```
	```console
	git config user.name <if name contains no spaces>
	```
	```console
	git config user.email <email-id>
	```
	```console
	- git config credential.username <user-id>
	```


- RENAME BRANCH:
	Renaming the branch
	```console
	git branch -m <oldname> <newname>
	```

- LOG HISTROY:
	To view the history of commits
	```console
	git log
	```
- Force RESET Git
	```console
	git reset --soft HEAD
	```

- Force UPDATE Git
	```console
	git push origin <branchName> --force
	```
