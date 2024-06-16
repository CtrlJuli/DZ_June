# DZ_June

# First Seminar
* Внести изменения
* Сохранить изменения (CTRL + S)
* Добавить с изменениями
* Зафиксировать/закоммитить файл
## git init
Создать репозиторий внутри папки
## git add
Добавить файл или файлы к следующему коммиту
## git status
Проверить состояние репозитория
## git diff
Увидеть разницу между сохраненным и зафиксированным файлом

## Цитаты
Для обозначения цитат в языке Markdown используется знак «больше» `>`. 
>Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. 

## Ссылки
Пример:

[Текст ссылки](https://www.example.com)

## Картинки
Пример:
![Сингапур](https://www.interfax.ru/ftproot/textphotos/2019/03/19/sin700.jpg)





# Second Seminar

## Creating branches
git branch branch_name - создание новой ветки

## Merging branching
git merge branch_name - слияние веток

## Conflicts
Конфликты возникают, когда затронуто общее рабочее пространство

## Deleting
git branch -d branch_name - удаление ветки

git branch -D branch_name - принудительное удаление ветки

## Checkout
git checkout branch_name - перейти на укаанную ветку

git checkout -b branch_name - создание новой ветки с переходом в нее

## Status
git status - отображение состояния файлов 

## Log
git log - просмотр журнала коммитов

git log --graph - выводит древо коммитов





# Работа с удаленными репозиториями

## Инструкция по синхронизации локального и удаленного репозиториев
1. Создать аккаунт на Gihub.com
2. Создать локальный репозиторий
3. "Подружить" ваш локальный и удаленный репозитории. Github при создании нового репозитория подскажет, как это сделать)
4. Отправить (push) ваш локальный репозиторий в удаленный (на Github), при этом вам, возможно, нужно будет авторизоваться на удаленном репозитории
5. Провести изменения "с другого компьютера"
6. Выкачать (pull) актуальное состояние из удаленного репозитория


## Инструкция по созданию pull request
1. Делаем форк (fork) интересующего нас репозитория
2. Делаем git clone для нашей версии этого репозитория
3. Доздаем ветку с предлагаемыми изменениями
4. Производим все изменения только в этой ветке
5. Отправляем эти изменения на свой аккаунт (push)
5. В окне на Github появляется возможность отправить pull request

