# Github Guide for Dummies
This contains all the necessary CMD line commands to execute and add new repositories in github. This will include adding new project, changing user name, global initialization of usernames. 


## Follow these methods to get started

- Git ORIGIN 
	ADD ORIGIN URL
	```console
	git add remote origin <github-url>
	```
	REMOVE ORIGIN URL
	```console
	git remote rm origin
	```
	VIEW ORIGIN URL
	```console
	git remote -v
	```
	RENAMING ORIGIN URL
	```console
	git remote set-url origin <new-url>
	```

- GIT PROCEDURE:
	ADD Files to staging
	```console
	git add .
	```
	COMMIT the changes
	```console
	git commit -m "init"
	```
	PUSH the changes to GITHUB
	```console
	git push origin master
	```

- Viewing GIT
	VIEW GIT USER and EMAIL credentials
	```console
	git config --global --list
	```
	VIEW USERNAME
	```console
	git config credential.username
	```
	VIEW USERNAME
	```console
	git config user.name
	```
	VIEW EMAIL
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
- FORCE RESET Git
	```console
	git reset --hard origin/master 
	```
- RESET to a previous COMMIT
	```console
	git reset <commithash>
	```
- FOURCE UPDATE
	```console
	git push origin <branchName> --force
	```
	
