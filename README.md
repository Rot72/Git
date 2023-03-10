# Git

[GitHub Styles](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

<h2>Start</h2>

```
git init
```

<h2>Status</h2>

Show report with untracked files:

```
git status
```

<h2>Add</h2>

Add untracked files:

```
git add .
```

<h2>Commit</h2>

Create the first commit

m = message
```
git commit -m "first commit"
```

Configure git

```
git config --global user.email <user.email>
git config --global user.name <user.name>
```

<br>

[Create repository](https://github.com/new)

<br>

Create link beetween project und repository

name = origin

url = urlRepository

```
git remote add <name> <url>
```

And then push using the remote name

<h2>Branch</h2>

Send changes to a branch

```
git push <nameBranch>
```

Logs from commit

```
git reflog
```

Makes it go back to a version chosen through the id of the log

```
git reset --hard <id>
```

New branch

```
git branch <nameBranch>
nameBranch = staging
```

Create a branch based on the main branch and select this

```
git checkout -b <nameNewBranch>
```

List the branches

```
git branch
```

Switch branch

```
git checkout <nameBranch>
```

**_before merging pull the files_**

```
git pull
```

<h2>Merge</h2>

Merging

```
git checkout <mainBranch>
git merge <nameBranch>
git push
```

<h2>Ignore</h2>

Ignore folders and files

```
touch .gitignore
```

<h2>Git errors:</h2>

> error: failed to push some refs to REPOSITORY

```
$ git push -f origin main
```



