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

* fatal: Unable to create '/home/devstack/Desktop/learn_node/node101/.git/index.lock': File exists.
```
sudo rm -f ./.git/index.lock
```

