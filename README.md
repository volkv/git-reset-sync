# Clear Commit History

```shell
git checkout --orphan latest_branch
```
```shell
git add -A
```
```shell
git commit -am ":tada:"
```
```shell
git branch -D main
```
```shell
git branch -m main
```
```shell
git push -f origin main
```

# Sync project with remote

```shell
rm -rf .git
```
```shell
git init
```
```shell
git remote add origin git@github.com:volkv/git-reset-sync.git
```
```shell
git fetch
```
```shell
git reset --hard origin/main
```
```shell
git checkout main
```
```shell
git pull
```

