# Шпоргалка

## Команды:
1. touch - создание файла в текущей папке
2. mkdir - создание папки в текущей папке
3. cd - перейти в нужную папку, cd ~ - вернуться в корневую папку, cd .. - перейти на уровень выше, в родительскую папку
4. ls - показывает все файлы и папки в этой папке
5. pwd - посмотреть в какой папке находишься
6. cp - копирование файла/папки
7. mv - перещение файла/папки
8. cat - посмотреть содержимое файла
9. rm - удаление файла, rm -r - удалить папку и всё что она содержит
10. rmdir - удалить папку

## Инструкция по инициализации проекта

1. git init - инициализировать папку репозитория, разгитить папку можно при помощи rm -rf .git
2. git status - проверить статус
3. git add - добавить файл;сразу все файлы git add --all
4. git commit -m 'Сообщение' - коммитим и присваиваем коммиту сообщение
5. git log - посмотреть историю коммитов
   
## Связываем локальный и удалённый репозиторий
Создаём репозиторий на сайте GitHub и берём от туда URL

1. git remote add origin URL - передаём название(origin) и URL на удалённый репозиторий
2. git remote -v - используем для того чтоб убедиться что репозиторий с удалённым связаны
3. git branch -M main - присваиваем основной ветке имя main
4. git push -u origin main - отправляем изменения
5. git push - отправить изменения на удалённый репозиторий

 
