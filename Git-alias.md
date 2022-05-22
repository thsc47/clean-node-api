[alias]
	s = !git status -s
	ca = !git add . && git commit -m
	c = git commit -m
	amend = !git add . && git commit --amend --no-edit
	l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s %C(cyan)[%cn] %C(green)%cr'
	bd = !git branch -D
	bc = !git checkout 
	b-b = !git checkout -b
