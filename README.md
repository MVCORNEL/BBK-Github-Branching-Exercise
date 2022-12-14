# A small git exercise on branching

## Step 1

**[CREATE README]**  
**[EDIT README]**  
**git init**  
**git add .**  
**git commit -m "Commit 0"**

## Step 2

**[EDIT README]**  
**git add .**  
**git status**  
**git commit -m "Commit 1"**  
**git log**

## Step 3

**[EDIT README]**  
**git add .**  
**git status**  
**git commit -m "Commit 2"**  
**git log**

## Step 4

**git checkout fbfb34e2ce9e5bfec49c0be77725636be7e69374**  
**git branch bug-fix**  
**git checkout bug-fix**  
**[EDIT README]**  
**git add .**  
**git commit -m "Commit 3"**  
**git log --graph**

## Step 5

**[EDIT README]**  
**git add .**  
**git commit -m "Commit 4"**

## Step 6

**git merge master**  
**[SOLVE MERGE CONFLICTS]**  
**[EDIT README]**  
**git add .**  
**git commit -m "Commit 5"**
