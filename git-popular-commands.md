#### Example Commands:

##### git add

- description: used for adding files to staging

Examples:
add all new files to staging

```
git add .
```

add specific file to staging

```
touch newFile.md
git add touch.md
```

#### git commit

- description: commits files from staging
- adds commit to git history with changes

Examples:

commit with one line and does not open text editor

```
git commit -m "updated a file"
```

commit and then write commit message in text editor
must save and quit file to complete commit

```
git commit
```

#### git push

- description: pushes commit history onto github

Examples:
push current branch

```
git push
```
