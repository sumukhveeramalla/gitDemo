# gitDemo
Learning GitDemo
<br/>
Hello Guys I am Learning
</br>
I will continue to learn.
<br/>
<br/>
U - Untracked -> new files that git doesn't yet track
<br />
M - Modified -> changed
<br/>
S - Staged -> file is ready to be commited
<br />
<br />
add - add new or changed files in your working directory to the Git staging area.
<br/>
git add <- file name ->
<br />
<br />
commit - It is the record of change
<br />
git commit -m "some message"
<br />
<br />
push -upload local repo content to remote repo
<br />
git push origin main
<br/>
init - used to create a new git repo
git init
git remote add origin <-link->
git remote -v (to verify remote)
git branch (to check branch)  -- master branch is the default branch
-- main branch is the branch present in github
you can try to rename

git branch -M main (to rename branch)
git push origin main

git checkout <-branch name -> (to navigate)
git checkout -b <-branch name -> (to create new branch)
git checkout -d <-branch name-> (to delete branch) -> you should present on other branch to delte other branch

Merging code:
git diff <-branch name-> (to compare commits, branches, files and more)
git merge <-branch name-> (to merge 2 branches)

pull request
It lets you tell others about changes you've pushed to a branch in a repository on GitHub.

git pull origin <-branch name->

Git Merge Conflicts

Undoing Changes
Case 1: staged changes
git reset <-file name -> 
git reset

Case 2: commited changes (for one commit)
git reset HEAD-1

Case 3:commited changes(for many commits)
git reset <-commit hash ->
git reset --hard <-commit hash->

Fork:
fork is a rough copy