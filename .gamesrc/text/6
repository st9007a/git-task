# Task 6 - Rebase

## Discuss About Previous Task

After revert the commit, your log will be like the follow:

```
* (HEAD -> master) Revert "Task 5"
|
|
* Task 5
|
|
* Merge branch 'feature2'
|\
| * (feature2) Task 4.2
| |
| * Task 4.1
* | Task 4.3
|/
* (feature1) Task 3
|
|
*  Task 2
|
|
*  Task 1
```

The content of HEAD is the same as the content of "Merge branch 'feature2'".

`git revert` will revert to previous commit and create a new commit to save it.

But Task 6 is generate, so the content of task file is different from the content of "Merge branch 'feature2'".

You can use `git stash` to stash current change and check task file.

## Description

Welcome to the most difficult task !

In this task, you should rearrange the nodes: "Task 4.1", "Task 4.2" and "Task 4.3".

Let these nodes locate at the same branch

## Steps

1. Commit current change
2. Rebase "feature2" branch

## Hint

- `git rebase`
- `git rebase --abort`
- `git rebase --continue`
- `git rebase --skip`
