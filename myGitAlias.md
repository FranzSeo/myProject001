### My Git Alias List
	cmp = "!f() { git add -A && git commit -m \"$@\" && git push; }; f"
	co = checkout
    rb = rebase -i
    st = status
    cm = commit
    pl = pull
    ps = push
    lg = log --graph --abbrev-commit --decorate --format=format:'%C(cyan)%h%C(reset) - %C(green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(yellow)%d%C(reset)' --all
    ad = add
    tg = tag -n
    df = diff
    br = branch
