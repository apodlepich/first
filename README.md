# Практическая работа №5
## Основы работы с системой контроля версий Git

Выполнил: Подлепич Артём  
Логин GitHub: apodlepich  


## 1. Создан аккаунт на GitHub
- Логин: **apodlepich** (первая буква имени + фамилия)

## 2. Создан репозиторий на GitHub
- Репозиторий создан **без README.md**

## 3. Инициализирован локальный репозиторий
```bash
$ git init
```

## 4. Создан файл .gitignore
```bash
$ cat .gitignore
# в каталогах bin и obj записываются скомпилированные файлы
*/bin/
*/obj/
# в каталоге .vs хранятся локальные настройки VisualStudio
.vs/
# в каталоге packages хранятся зависимости
packages/
```

## 5. Настроен пользователь Git
```bash
$ git config user.name "apodlepich"
$ git config user.email "art29752007@gmail.com"
$ git config --global http.sslVerify false
```

## 6. Добавлены файлы и создан коммит
```bash
$ git add .
$ git commit -m "Initial commit: добавлен .gitignore"
[main (root-commit) 21761b9] Initial commit: добавлен .gitignore
 1 file changed
 create mode 100644 .gitignore

```

## 7. Привязан удалённый репозиторий
```bash
$ git remote add origin https://github.com/apodlepich/first.git
$ git remote -v
origin  https://github.com/apodlepich/first.git (fetch)
origin  https://github.com/apodlepich/first.git (push)
```

## 8. Проверка состояния и истории
```bash
$ git status
On branch main
nothing to commit, working tree clean

$ git log --oneline
62c2225 (HEAD -> main, origin/main, origin/HEAD) Initial commit
```

## 9. Просмотр информации о коммите
```bash
$ git show HEAD
commit 62c222520e1c7effcfa045efb9fb490410accf0a (HEAD -> main, origin/main, origin/HEAD)
Author: apodlepich <art29752007@gmail.com>

Date:   Fri Apr 10 21:42:22 2026 +0300

```

## 10. Проверка веток
```bash
$ git branch
* main
```

## 11. Проверка изменений
```bash
$ git diff HEAD
(изменений нет)
```


## Ссылка на репозиторий

https://github.com/apodlepich/first
