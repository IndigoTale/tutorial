# Gitコマンド備忘録

## git clone ~ first commit

```bash
git clone git https://github.com/(yourAccount)/yourRepogitory).git
git add README.md //README.mdを編集した後
git commit -m "add README.md"
git push -u origin master
```

## create develop branch

```bash
> git branch
* master
> git branch develop master
> git branch
  develop
* master
> git checkout develop
Switched to branch 'develop'
> git branch
* develop
  master
> mkdir src && touch hello.py
> git add src/hello.py
> git commit -m "add src/hello.py"
> git push origin develop
```

## create feature branch

```bash
> git branch feature/update_README develop
> git checkout feature/update_README
// Edit README.md
> git add README.md
> git commit -m "update README.md"
> git push origin feature/update_README
```