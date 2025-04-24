# How to use to different account of github for personal use and profession use

## Steps to push code for primary account:

### For first time

1. git init
2. git add .
3. git commit -m "message"

NOTE: If host is "github.com" in ~/.ssh/config for primary account then don't modify the origin url.

6. git remote add origin git@github.com:username/repo.git ( git remote add origin git@github.com:username/repo.git = for this case )
7. git push -u origin main

### OR

NOTE: But if it is like "github.com-personal" then modify origin url as follows.

6. git remote add origin git@github.com-yoursshhost:username/repo.git ( git remote add origin git@github.com-personal:username/repo.git )
7. git push -u origin main

### After first

1. git add .
2. git commit -m "message"
3. git push
