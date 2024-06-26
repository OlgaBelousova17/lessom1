# Подсказка по GIT

## Привестсвие с GIT

1. *Создание имени*

>**Создание имя и емэйла --global дает нам возможность глобально внести свои данные. То есть при запуске программы еще раз, для создания нового файла, нам не надо повторно вводить свои данные, как с функцией --local.**

```sh
git config --global user.name "Name"
```


2. *Создание емэйла*
```sh
git config --global user.email
```

3. *Создание имени и емэйла для одной работы*
```sh
git config --local
```
4. *Для отображения папок*
 
 На Windows
```sh
dir
```
На MacOs, Linux

```sh
ls
```

5. *Для отображения пути к папке*
```sh
pwd
```
## Создание репозитория
1. *Отображает или созздает папку, в которой будем работать*

```sh
git init
```
2. *Показывает статус папки. Были ли в ней изменения или нет*
>**Если выделено красным, значит файл не отслеживается. Если зеленый, значит отслеживается. Чтобы файл отслеживался его надо индексировать.**

```sh
git status
```
3. *Индексация (сохранение) неотслеживаемого (измененного) файла*
```sh
git add
```
4. *Закрепление измененного файла*
```sh
git commit -m "Message"
```
## Удаления

1. *Почистить терминал*

```sh
clear
```
2. *Удаление файла*
```sh
git -d <Название фвйла>
```
3. *Насильственное удаление файла*
>**На случай, если простое удаление не получается**

```sh
git -D <Название файла>
```
4. *Тоже удаление файла*
```sh
git rm. <Название файла>
```
5. *Удалить изменения*
```sh
git restore --staget <Название файла>
```



## Работа с ветками

1. *Показывает обширно ветки*
```sh
git log
```
2. *Показывает ветки коротко*
```sh
git log --oneline
```
3. *Переносит на другую ветку*
```sh
git checkout <Название ветки>
```

конфликт git checkout <name>


4. *Отображает все действующие ветки*

```sh
git branch
```
5. *Создание новой ветки*
```sh
git branch <название ветки>
```
6. *Визуализация ветки*
```sh
git log --graph
```
7. *Когда в терменале появилась строка **END**, команда помогает продолжить работу*
```sh
q
```

8. *Перенос черновика в чистовик*
```sh
git merge <Название ветки>
```

9. *Показать отличия*

```sh
git diff
```