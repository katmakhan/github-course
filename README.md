# github-free-course
This contains all the necessary CMD line commands to execute and add new repositories in github. This will include adding new project, changing user name, global initialization of usernames. 


## Follow these methods to get started

- REMOVE ORIGIN (IF entered Wrong)
	```console
	git remote rm origin
	```
	```console
	git remote -v - To view the origin
	```

- GIT PROCEDURE:
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
	```console
	git config --global --list
	```
	```console
	git config credential.username
	```console
	git config user.name
	```
	```console
	git config user.email
	```


- TODO:

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
	```console
	git branch -m <oldname> <newname>
	```
- RENAME ORIGIN:
	```console
	git remote set-url origin <new-url>
	```
	
- LOG HISTROY:
	```console
	git log
	```