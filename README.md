PRECONDITIONS: git installed and configured
1. From console: mkdir new-project
2. cd new-project
3. touch README.md
4. fill README.md with initial info
4. git add README.md
5. git commit -m "init"
6. git push
6. git checkout -b development
7. make needed changes to README.md
8. git add README.md
9. git commit -m "README update"
10. git push --set-upstream origin development
11. git checkout main
12. git merge development