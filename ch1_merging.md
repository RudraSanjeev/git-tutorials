#### How to create new branch pull, push, best practices :

- to create new branch

```git
    git branch -b <branch_name>
```

- to delete branch

```git
    git branch -d <branch_name>
```

- to merge to master
  - first checkout to master then

**Note:**

- It is best idea to first pull from the master and then make changes inside newly created branch (must if your branch persist for longer time)
- This reduce chances of conflicts
- to pull from master
- make sure You are in newly created branch

```git
    git pull origin master
```

-

```git
    git merge <branch_name>
```
