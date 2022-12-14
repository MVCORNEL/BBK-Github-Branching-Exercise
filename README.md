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

## Step 7

**[EDIT README]**  
**git add .**  
**git commit -m "Commit 6"**

## Step 8

**git checkout e5b39ec**  
**git branch bug-fix-experimental**  
**git checkout bug-fix-experimental**  
**[EDIT README]**  
**git add .**  
**git commit -m "Commit 7"**

## Step 9

**[EDIT README]**  
**git add .**  
**git commit -m "Commit 8"**

## Step 10

**[EDIT README]**  
**git add .**  
**git commit -m "Commit 9"**

## Step 12

**git checkout bug-fix**  
**git merge bug-fix-experimental**  
**[SOLVE MERGE CONFLICTS]**  
**[EDIT README]**  
**git add .**  
**git commit -m "Commit 11"**

## Step 13

**[EDIT README]**  
**git add .**  
**git commit -m "Commit 12"**
