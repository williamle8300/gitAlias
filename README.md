gitAlias
========

[alias]
	a = add .
	b = branch
	c = commit -m
	co = checkout
	l = log
	p = push
	s = status
	ac = "!git add -A && git commit -m"
	acp = "!git add -A && git commit -m 'routine saving...' && git push"
	cos = "!git checkout $1 && git status"
	cray1 = fetch origin
	cray2 = reset --hard origin/master
