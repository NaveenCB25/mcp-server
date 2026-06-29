# mcp-server
#2 
$ git init
$ touch file1.txt
$ git add .
$ git commit -m "Initial commit"
$ git branch feature-branch
$ git checkout feature-branch
$ git switch feature-branch
$ notepad file1.txt
$ git add .
$ git commit -m "Updated file in feature branch"
$ git checkout master
$ git switch master
$ git merge feature-branch
$ notepad file1.txt
$ git stash
$ git checkout feature-branch
$ git stash apply
$ git status
#3
git init
git add .
git commit -m "Initial commit"
git tag v1.0
git tag v1.0 <commit-id>
git tag
#4
git cherry-pick <start-commit>^..<end-commit>

git checkout <target-branch>
git cherry-pick <start-commit>^..<end-commit>
git status
git add .
git cherry-pick --continue
#5
git show <commit-id>
git show ab2c3d
#6
git log --author="John Doe" --since="2023-01-01" --until="2023-12-31"
#7
git log -5
git log -5 --oneline
#8
git revert id
