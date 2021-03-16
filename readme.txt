This is a txt about git-study.

Some usual git commads:

git config --global user.<name/email> "<...>"
git init
git status
git add <file>
git commit -m "<message>"
git log
git reflog
git reset --hard commit_id	//HEAD^ HEAD^^ HEAD~n
git diff HEAD -- <file>
git checkout -- <file>		//let the work file come back to latest of <git commit> or <git add>
git reset HEAD <file>		//unstaged to the work_area

```how to backtracking to the latest version when you has add the file to stage
git reset HEAD -- <file>
git checkout -- <file>
```

git rm <filename>	//delete both stage and work_area file

branch test

You can use these usual commads to manage your branch:

git branch		//view branchs

git branch <branch_name>	//create a branch

git checkout <branch_name>	//switch to the branch, in later version, you can also use    git switch <branch_name>    to do this

git checkout -b <branch_name>	//create and switch to this new branch, also in later version, you can   git switch -c <branch_name>

git merge <branch_name>		//merge the branch with current branch

git branch -d <branch_name>	//delete a branch

<<<<<<< HEAD
Creating a new branch is quick and simple.
=======
Creating a new branch is quick and simple.
>>>>>>> feature1



edit on the new branch.


working branch--->work

Attention please:
you must to confirm that you have add the files which you have edit to the git(you don't need to submit but you must to add!!!)
