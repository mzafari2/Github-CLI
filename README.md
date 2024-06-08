## check https://cli.github.com/manual/gh

List all public repos:
```
$ gh repo list 
```

List all labels: 
```
$ gh label list
```

create new label:
```
$ gh label create bug --description "Something isn't working" --color E99695
```

create a new git repo
```
$ gh repo create
```

Delete a GitHub repository. With no argument, deletes the current repository
```
$ gh repo delete [<repository>]
```

confirm deletion without prompting 
```
--yes 
```

Rename a GitHub repository, default renames the current repository:
```
gh repo rename [<new-name>]
```