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

name: origin

url: urlRepository

```
git remote add <name> <url>
```



Send changes

```
git push

```

<h2>Git errors:</h2>

> error: failed to push some refs to REPOSITORY

```
$ git push -f origin main
```



