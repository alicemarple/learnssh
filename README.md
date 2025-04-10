# How to use to different account of github for personal use and profession use

## Steps to push code for primary account:

### For first time

1. git init
2. git add .
3. git commit -m "message"

NOTE: origin url must modify from original. But in ~/.ssh/config github host for primary account is "github.com" then don't modify the origin url.

6. git add origin git@github-yourSSHhost:username/repo.git ( git remote add origin git@github.com:username/repo.git = for this case)
7. git push origin main

### OR

NOTE: But it is like "github.com-personal" then modify origin url as follows.

6. git add origin git@github-yourSSHhost:username/repo.git ( git remote add origin git@github.com-personal:username/repo.git )
7. git push origin main

### After first

1. git add .
2. git commit -m "message"
3. git push origin main
