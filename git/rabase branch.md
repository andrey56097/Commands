// get last from master
update main branch

git checkout YOUR_BRANCH
git rebase master

git add -u // necessary

// fix conflicts and than
git rebase --continue 
git push origin YOUR_BRANCH -f

git reset HEAD~1

____________________________________________________

1. Получить последние изменения из main:

```git fetch origin master```

2. Проверьте свою ветку функций:

```git checkout YOUR_BRANCH```

3. Перебазируйте его против main:

```git rebase origin/master```

4. Force-push в вашу ветку.

```git push --force origin YOUR_BRANCH```

_____________________________________________________
https://docs.gitlab.com/ee/topics/git/git_rebase.html
