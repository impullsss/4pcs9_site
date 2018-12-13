# 4pcs9_site

Учебный проект

## git

### установка

Установить средства для работы с git можно тут https://gitforwindows.org/

Я рекомендую работать с git из командной строки и не использовать GUI.

### настройка
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
``` 

### начало работы с проектом
```
cd /c/путь/к/папке/с/проектами
git clone git@github.com:impullsss/4pcs9_site.git
cd 4pcs9_site
```

### работа над задачей
Сначала убедиться, что вы на ветке `master` и у вас не осталось незакмомиченых изменений после выполнения предыдущей задачи.
```
git status
```

Обновить ветку `master`.
```
git pull
```

Создать свою ветку от `master`. Одна задача = одна ветка.
```
git checkout -b my-branch-name
```

Внести изменения в код в соответствии с задачей.

Добавить измененные файлы в коммит командой `git add имя_файла`. Контролировать процесс командой `git status`.

Создать коммит из добавленных файлов.
```
git commit -m 'Описание коммита'
```

Залить вашу ветку с вашими коммитами в репозиторий.
```
git push
```

Создать pull-request на вливание вашей ветки с вашими коммитами в ветку `master`

https://help.github.com/articles/using-pull-requests
