Cостояние рабочего каталога и раздела проиндексированных файлов

```
git status
```

Добавить изменения в конкретном файле

```
git add [path/to/file]
```

Добавить все изменения из текущей папки

```
git add .
```

Добавить все изменения проекта, назвисимо от уровня вложенности (если текущая папка - /src/hooks, то добвяться и изменения из папки /src/components)

```
git add -A
```

Создать коммит

```
git commit -m "message"
```

Изменить послений коммит - добавить еще изменений и изменить сообщение

```
git commit --amend -m "message"
```

Добавить все изменения и создать коммит

```
git commit -a -m "message"
```

Добавить все изменения и создать коммит (сокращенный вариант)

```
git commit -am "message"
```

Первать мёрдж (если есть конфликты)

```
git merge --abort"
```

Откатить коммит

```
git revert [hash]"
```

Удлить локальную ветку

```
git branch -D [name]
```

Окатить изменения в файле

```
git checkout -- [path/to/file]
```

Откатить изменения в текущей папке

```
git checkout -- .
```

Переключить ветку

```
git checkoout [branch]
```

Показать удаленные подключения к другим репозиториям (по url).

```
git remote -v
```

```
git remote add origin [ssh]
```

```
git remote set-url origin [ssh]
```

Загрузить изменения из удаленного репозитория

```
git pull origin [branch]
```

Отпраивить изменения в удаленный репозиторий

```
git push origin [branch]
```

Отключить игнорирование изменение ригистра в названиях файлов/папок

```
git config core.ignorecase false
```

Отменить последний коммит (изменения вернуться в stage)

```
git reset --soft HEAD~1
```

---

Error

```
warning: CRLF will be replaced by LF in .prettierrc.
The file will have its original line endings in your working directory
```

Solution

```
git config core.autocrlf true

```
