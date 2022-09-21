**Get current branch name**:
```sh
# https://stackoverflow.com/a/11868440

# errors when in detached HEAD, no stdout; works right after git init
git symbolic-ref --short HEAD 
# prints HEAD when in detached HEAD or after git init; errors after git init
git rev-parse --abbrev-ref HEAD
```
