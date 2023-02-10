# gitflow-example

![Screenshot_1](https://user-images.githubusercontent.com/91306218/218127890-9aea3f64-b85c-47c1-a881-35d9f62e95d1.png)

## gitflow rules

1. Создать репозиторий и клонировать его на компьютер
2. Создать ветку разработки develop от главной ветки (master, main)
3. Создать от ветки develop feature/ -ветки и мержить feature/ -ветки в develop, когда фичи будут выполнены.
4. Создание ветки release/0.1.0 от develop (в ней исправляются баги)
5. Когда ветка release/0.1.0 закончена, то она мержится сначало в main. Затем она же мержится в develop и затем удаляется
6. Если в ветке main обнаруживается ошибка, то от ветки main создается hotfix-ветка 
7. Когда работа над hotfix-веткой завершается, то ее нужно мержить в develop и main

## git commands
1. git status
2. git add . - добавляет файлы в stage
3. git commit -m "comment" - запись комита
4. git log / git log --oneline
5. git push [rep_link] [branch_name] - отправить ветку на GITHUB
6. git reset - удаляет файлы из stage
7. git reset --hard - возвращает весь код на последний коммит
8. git diff - показать изменения
9. git branch - показать ветки
10. git branch [branch_name] - создать ветку
11. git checkout [branch_name] - перейти на ветку
12. git remote -v
13. git pull [rep_link] [branch_name] - вытащить ветку из GITHUB
14. git branch -d [branch_name] - удалить ветку
15. git merge [branch_name] - переместить код с ветки которую вы указали на ветку в которой вы в данный момент находитесь
16. git checkout -b [branch_name] - создать новую ветку и сразу же перейти на нее
