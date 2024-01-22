# Github Guide for Dummies
This contains all the necessary CMD line commands to execute and add new repositories in github. 
- Adding new project
- changing user name
- global initialization of usernames
- Renaming branch
- Adding to remote repo in github


## Follow these methods to get started

- GIT ORIGIN 
	- ADD ORIGIN URL
	```console
	git remote add origin <github-url>
	```
	- REMOVE ORIGIN URL
	```console
	git remote rm origin
	```
	- VIEW ORIGIN URL
	```console
	git remote -v
	```
	- RENAMING ORIGIN URL
	```console
	git remote set-url origin <new-url>
	```

- GIT PROCEDURE:
	- ADD Files to staging
	```console
	git add .
	```
	- COMMIT the changes
	```console
	git commit -m "init"
	```
	- PUSH the changes to GITHUB
	```console
	git push origin master
	```

- VIEW GITHUB CREDENTIALS
	- VIEW GIT USER and EMAIL credentials
	```console
	git config --global --list
	```
- CHANGE GITHUB CREDENTIALS
	- CHANGE USERNAME
	```console
	git config user.name <name>
	```
	- CHANGE EMAIL
	```console
	git config user.email <email>
	```


- TODO
	If you want to change the username and user email for the individual project
	- Change the email
	```console
	git config user.email <email-id>
	```
	- Change the username
	```console
	- git config credential.username <user-id>
	```
	- NOTE:
		- Changing the name, whether name contains spaces or not
		```console
		git config user.name "<if name with spaces>"
		```
		```console
		git config user.name <if name contains no spaces>
		```


- RENAME BRANCH
	- Renaming the branch
	```console
	git branch -m <oldname> <newname>
	```

- LOG HISTROY
	- To view the history of commits
	```console
	git log
	```
- FORCE RESET
  DO it after the `git pull origin master`, to forcefully make it same as the remote branch
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
	
