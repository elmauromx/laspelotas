# DevOps GIT Journal
## Date 20180703

### What did I learn today?

1. How to download Git local repository
2. Install Git
3. How to make a MarkDown document (You are reading it)
4. Create a local repository
5. Clone rempote repository to a local repository
6. How to stage modified files
7. How to commit changes on modified files to master branch
8. Github charges you $7.00 USD at month to have private repositories
9. git reset can be use to rollback a file already uploaded to stage already
10. git commit components
      1. id. A hash for the commit
      1. Author
      1. Date
      1. email
      1. comment
11. How to change date on an already commited change
```bash
git filter-branch --env-filter
    'if [ $GIT_COMMIT = 45ce30ca7d6545a750b549f9dc3de9f6f3617f02 ]
     then
         export GIT_AUTHOR_DATE="Tue Jul 3 20:57:32 2018 -0500"
         export GIT_COMMITTER_DATE="Tue Jul 3 20:57:32 2018 -0500"
     fi'
```
1. How to add aliases on git (with commands):
```bash
git config --global alias.undo 'reset --soft HEAD^'
```

### Are there any impediments or doubts for the next lesson?

* Air Conditioner is not working well
* There is never coffee on cafeteria

### Reference Material

* Training Lab Reference: https://gist.github.com/walreyes/af56e2b9a70a3eab59be599f61835644
* Adding existing project to GitHub:  https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/
* Markdown Cheat Sheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
