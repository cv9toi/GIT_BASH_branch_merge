1. На локальном репозитории сделать ветки для:
- Postman
git branch Postman

- Jmeter
git branch Jmeter

- CheckLists
git branch CheckLists

- Bag Reports
git branch BagReports

- SQL
git branch SQL

- Charles
git branch Charles

- Mobile testing
git branch MobileTesting


2. Запушить все ветки на внешний репозиторий
git push --all

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
touch bagreport.txt

4. Запушить структуру багрепорта на внешний репозиторий
git push --set-upstream origin BagReports

5. Вмержить ветку Bag Reports в Main
git merge BagReports -m "merge Bagreports"

6. Запушить main на внешний репозиторий.
git push 

7. В ветке CheckLists набросать структуру чек листа.
touch checklist.txt
vim checklist.txt

8. Запушить структуру на внешний репозиторий
git push --set-upstream origin CheckLists

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main
git fetch
git pull
