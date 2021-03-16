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
