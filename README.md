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
*/bin/
*/obj/
.vs/
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
git commit -m "first commit"
[main fd126e7] first commit
 1 file changed, 10 insertions(+), 11 deletions(-)

```

## 7. Привязан удалённый репозиторий
```bash
$ git remote add origin https://github.com/apodlepich/first.git
$ git remote -v
origin  https://github.com/apodlepich/first.git (fetch)
origin  https://github.com/apodlepich/first.git (push)
```

## 8. Проверка состояния
```bash
$ git status
On branch main
nothing to commit, working tree clean

```

## 9. Проверка веток
```bash
$ git branch
* main
```

## 10. Проверка изменений
```bash
$ git diff HEAD
(изменений нет)
```

https://github.com/apodlepich/first
