# 2022 03 08: Git Basics

- `git init`: initialize git repository in current location
    - make sure you do not nest git repositories
- `git status`: tells you the current status
- `git add <FILE>`: put <FILE> into the staging area
- `git commit`: write a commit + message for files in staging
    - `git commit -m "MESSAGE"`: writes a commit message in-line

- `git log`: shows you the git log / commit history
    - hit "q" to quit if it's too long
    - `git log --oneline`: gives you the shortened oneline version of log
    - `git log --oneline --all`: show you all the history

- `git diff`: shows you new changes that have not been committed
- `git diff --staged`: shows you diff for files in staging area
- `git diff <HASH> <FILE>`: shows you the differences between HASH and current file
    - HEAD~1: HEAD one commit back
    - 3j378dj: or you can use the commit hash directly


- `git checkout <HASH>`: take you do <HASH> location
    - `git checkout main`: take you back to the `main` branch
- `git checkout <HASH> <FILE>`: retore <FILE> from version in <HASH>

## REMOTES

- `ssh-keygen`: create an ssh key
    - copy your `id_rsa.pub` into your ssh keys in your account
    - use the SSH url for github, not HTTPS

- `git remote add origin <URL>`: sets up the remote called origin with <URL>
- `git rmote rm origin`: remote remote (can use this to "rename")
    
- `git push origin main`: sends code from computer to remote
- `git pull origin main`: updates local code with remote code
