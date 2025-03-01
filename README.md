# rzrasel-tutorial-git-tool
Rz Rasel Tutorial Git Tool

The "rzrasel-tutorial-git-tool" branch is dedicated to creating tutorials on "git" and various topics. Here is a tutorial on "git" and various topics

### Rz Rasel - Gitflow Local Tutorial - [How to use Gitflow - Bangla Tutorial](https://youtu.be/nXW_DVQoW0E)

```git_flow_local_tutorial
// Regular Git Command
// ---- git init
mkdir rzrasel-gitflow-tutorial
cd rzrasel-gitflow-tutorial/
ll
git status
git init
git status
clear
git log --oneline
clear
git flow -h

// Git Flow Command
git flow init
----------------[(Accepted All Default By Pressing Enter)]
git status
git branch
git flow -h
git flow feature -h
git flow feature list
--------------------------------Feature Branch gitflow-tutorial
git flow feature start gitflow-feature [(if multple word use quate)]
clear
git branch
git flow feature list
----------------[(Add And Work In A File)]
// touch gitflow-feature.txt
// echo "gitflow-feature" > gitflow-feature.txt
git add .
git commit -m "Git Flow Feature Complete Rz Rasel"
git log --oneline
git flow feature finish gitflow-feature
git branch
git flow feature list
clear
ll
git log
clear
--------------------------------Release Branch 0.0.1
git flow release start 0.0.1
----------------[(Add And Work In A File)]
git add .
git commit -m "Git Flow Release Fixed Rz Rasel"
git flow release finish 0.0.1
i
esc
:wq
---- ---- ---- ----Tag
i
tag v-0.0.1
esc
:wq
---- ---- ---- ----Merge Commit
i
esc
:wq
--------------------------------Hotfix Branch gitflow-hotfix
git flow hotfix start gitflow-hotfix
----------------[(Add And Work In A File)]
git add .
git commit -m "Git Flow Hotfix Fixed Rz Rasel"
git flow hotfix finish gitflow-hotfix
i
esc
:wq
---- ---- hotfix (Tag)
tag v-0.0.1
esc
:wq
---- ---- ---- ----hotfix Merge Commit
i
esc
:wq
------------------------------------------------
```

### Rz Rasel - Gitflow Remote Tutorial - [Gitflow on GitHub: How to use Git Flow workflows with GitHub Based Repos](https://youtu.be/WQuxeEvaCxs)

```git_flow_remote_tutorial
// Regular Git Command
git init
git remote add origin [remote-repository-url]
git remote -v
git fetch
git checkout master

// Git Flow Command
git flow init
git branch -a
git push origin
git push --set-upstream origin development
--------------------------------Feature Branch Gitflow Tutorial
git flow feature start gitflow-feature
git branch -a
--------------[(Add And Work In A File)]
git add .
git commit -m "Git Flow Feature Complete Rz Rasel"
git flow feature finish gitflow-feature
git branch -a
ls
git push origin
--------------[(Watch Remote Git Account)]
--------------------------------Release Branch 0.0.1
git flow release start '0.0.1'
git branch -a
git push origin
git push --set-upstream origin release/0.0.1
--------------[(Add And Work In A File)]
git add .
git commit -m "Git Flow Release Fixed Rz Rasel"
git push origin
git flow release finish '0.0.1'
i
esc
:wq
---- ---- ---- ----Tag
i
tag v-0.0.1
esc
:wq
---- ---- ---- ----Merge Commit
i
esc
:wq
git branch -a
ls
git checkout master
ls
git push origin
git tag -l
```

### Rz Rasel - Gitflow Extra Tutorial
```
------------------------------------------------
git flow init
// Git Flow pull/push
git flow feature pull <branch-name>
git flow feature publish <branch-name>
// Git Checkout
git checkout develop
git merge feature_branch
git flow feature finish feature_branch
------------------------------------------------
```

[Git Flow Part 3 - Learn Git Flow commands | How to use Git Flow Tutorial](https://youtu.be/ye4LVrQ0TuM)

# Rz Rasel Git Tutorial
### Rz Rasel Git Tutorial
- Git Commit Number - 9
- Git Commit Number - 8
- Git Commit Number - 7
- Git Commit Number - 6
- Git Commit Number - 5
- Git Commit Number - 4
- Git Commit Number - 3
- Git Commit Number - 2
- Git Commit Number - 1