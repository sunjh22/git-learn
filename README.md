This is a git learning notebook

	$ git version 1.8.3.1
	$ git config --global user.name ""
	$ git config --global user.email ""
	$ git config --global color.ui true
	$ git init
	$ git status
	$ git add README
	$ git commit -a
	$ git diff
	$ git log
	$ git reset HEAD README.md
	$ ssh-keygen -b 2048
	$ git remote add origin git@github.com:sunjh22/git-learn.git
	$ git push origin master
	$ git clone
	$ git pull origin master
	$ git checkout -- README.md
	$ git stash
	$ git stash pop
	$ git commit --amend
	$ git branch readme-changes
	$ git checkout readme-changes
	$ git merge readme-changes
	$ git log --pretty=oneline --abbrev-commit --graph --branches
	$ git branch --all
	$ git push origin readme-changes
