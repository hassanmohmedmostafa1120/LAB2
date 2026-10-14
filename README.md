# LAB2

## 1. Create Repository and First Commit

```bash
mkdir LAB2
touch index.html
git add .
git commit -m "intial commt"
```

## 2. Branches and Merging

```bash
git branch test
git branch dev
git switch dev
touch style.css
git add .
git commit -m "add syle"
git switch test
touch script.js
git add .
git commit -m "add script"
git switch main
git merge test
git merge dev
git push -u upstream main
```

## 3. Remove Remote Branch and Local Branch

```bash
git push origin :branch_name
git branch -d branch_name
```

## 4. Get Stash

```bash
git stash
```

## 5. Git Tags

```bash
git tag -a v1.7 -m "version 1.7"
git push origin
git push --tags
git tag
```

## 6. Delete Git Tag

```bash
git push origin --delete v1.7
git tag -d v1.7
```

## 7. Add an Image to README

Download an image and put its path into README.

```markdown
![Image](img.jpeg) 
```


