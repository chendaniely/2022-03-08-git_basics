# 2022-03-08-git_basics

- `git init`: initialize git repository in current location
    - make sure you do not nest git repositories
- `git status`: tells you the current status
- `git add <FILE>`: put <FILE> into the staging area
- `git commit`: write a commit + message for files in staging
    - `git commit -m "MESSAGE"`: writes a commit message in-line

- `git log`: shows you the git log / commit history
    - hit "q" to quit if it's too long
    - `git log --oneline`: gives you the shortened oneline version of log

- `git diff`: shows you new changes that have not been committed
- `git diff <HASH> <FILE>`: shows you the differences between HASH and current file
    - HEAD~1: HEAD one commit back
    - 3j378dj: or you can use the commit hash directly

