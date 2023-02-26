# rzrasel-tutorial-git-tool
Rz Rasel Tutorial Git Tool

The "rzrasel-tutorial-git-tool" branch is dedicated to creating tutorials on "git" and various topics. Here is a tutorial on "git" and various topics

### Rz Rasel - Gitflow Local Tutorial - [How to use Gitflow - Bangla Tutorial](https://youtu.be/nXW_DVQoW0E)

```git_flow_local_tutorial
// Regular Git Command
git init
git flow init

// Git Flow Command
----------------[(All Accepted By Pressing Enter)]
git branch
--------------------------------Feature Branch gitflow-tutorial
git flow feature start gitflow-tutorial [(if multple word use quate)]
----------------[(Add And Work In A File)]
git add .
git commit -m "Git Flow Tutorial Rz Rasel"
git flow feature finish gitflow-tutorial
--------------------------------Release Branch 0.0.1
git flow release start 0.0.1
----------------[(Add And Work In A File)]
git add .
git commit -m "Git Flow Release Bug Fixed Rz Rasel"
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
git commit -m "Git Flow Hotfix Bug Fixed Rz Rasel"
git flow hotfix finish gitflow-bugfix
i
esc
:wq
---- ---- hotfix (Tag)
hotfix-tag v-0.0.1
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
--------------------------------Branch Gitflow Tutorial
git flow feature start gitflow-tutorial
git branch -a
--------------[(Add And Work In A File)]
git add .
git commit -m "Git Flow Tutorial Rz Rasel"
git flow feature finish gitflow-tutorial
git branch -a
git push origin
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

# Rz Rasel Git Tutorial
### Rz Rasel Git Tutorial
- Git Commit Number - 7
- Git Commit Number - 6
- Git Commit Number - 5
- Git Commit Number - 4
- Git Commit Number - 3
- Git Commit Number - 2
- Git Commit Number - 1