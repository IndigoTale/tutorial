# Gitコマンド備忘録

## git clone ~ first commit

```bash
git clone git https://github.com/(yourAccount)/yourRepogitory).git
git add README.md //README.mdを編集した後
git commit -m "add README.md"
git push -u origin master
```

## create branch for development

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
```
