#### What is git
```
```

* Intialize
```
git init
```

* Logs
```
git logs
```

* adding to staging 
```
git add <file-one>
git add <file-two>
```

* adding file from a particular folder to staging area
```
git add --add snippet/
```

* commiting
```
git commit -m 'commit message'
```

* Files or folder to be ignored via .gitignore
```
vi .gitignore

env/
*.db
*.pyc

git add .gitignore
```

* working directory ---> staging area ---->Repository

* diff b/w working directory and stating area
```
git diff
```

* diff b/w staging area and respository
```
git diff --staged
```

* diff b/w commit in repository
```
git diff id1 id2l
```

* Editing commit message
```
```

* Git tags
```
```

* Git branches
```
```
* Removing files from staging area
```
git reset
```

* Remove a single file from staging are
```
git reset <file-name>
```

* fatal: Unable to create '/home/devstack/Desktop/learn_node/node101/.git/index.lock': File exists.
```
sudo rm -f ./.git/index.lock


* Rules for git commit-message
1. Heading in less than 50characters
2. A blank line
3. Why, what and how
```

