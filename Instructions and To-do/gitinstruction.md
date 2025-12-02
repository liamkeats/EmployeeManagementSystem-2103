## how to use the git brandi

This is how we will work together on the project using git

---

### 1. Getting the latest version

whenever you are working:

1. open a terminal in the project folder. this is where you see employee_management.c
2. run:

```bash
git pull
```
### 2. Saving and pushing your changes

when finished working, make sure you do these terminal commands in order.

```bash
git add .
git commit -m "any message about the updates you made"
git push origin main
```

this will push the files you worked on into github so i can then pull your progress. 

## 3. Error fixing
if for some reason your remote origin becomes broken. open in terminal the folder that contains your project

```bash
git init
git add .
git commit -m "readding my remote origin"

git branch -M main
git remote add origin https://github.com/brandiballer/FinalProject-V2.git
git push -u origin main
```

then after everything is working again check with

```bash
git status
```

then you can do

```bash
git add .
git commit -m "your message"
git push
```