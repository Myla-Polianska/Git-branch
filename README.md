# Git-branch
Task | Solution 
:---|:------
На локальном репозитории сделать ветки для: Postman, Jmeter, CheckLists, Bag Reports, SQL, Charles, Mobile testing | git branch [branch name]
Запушить все ветки на внешний репозиторий | git checkout [branch name], git push -u origin [branch name]
В ветке Bag Reports сделать текстовый документ со структурой баг репорта | git checkout BugReports, cat > bug_report.txt  
Запушить структуру багрепорта на внешний репозиторий | git add., git commit -m "message", git push
Вмержить ветку Bag Reports в Main | git checkout main, git merge BugReports 
Запушить main на внешний репозиторий | git push
В ветке CheckLists набросать структуру чек листа | git checkout CheckLists , cat > check_list.txt
Запушить структуру на внешний репозиторий | git add., git commit -m "message", git push
На внешнем репозитории сделать Pull Request ветки CheckLists в main | go to main branch a click on "pull request" , then click on "merge"
Синхронизировать Внешнюю и Локальную ветки Main | git checkout main, git pull
