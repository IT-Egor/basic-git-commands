# Основные команды Git

## Терминология 

**Репозиторий (_repository_)** — папка, в которой Git отслеживает изменения  
**Коммит (_commit_)** - сохранение состояния файлов  
**Ветка (_branch_)** - история коммитов  
**Клонирование (_clone_)** - копирование удалённого репозитория на локальный компьютер  

## Команды 

### Локальный репозиторий
- ```git init``` - подключить гит в папке  
- ```rm -rf .git``` - отключить гит в папке  
- ```git status``` - статус репозитория  
- ```git add <имя>``` - обновить информацию о файле  
`--all` - обновить информацию о всех файлах  
`.` - обновить всю папку  
- ```git commit``` - создать коммит  
`-m` - добавить комментарий (указать в кавычках)  
- ```git log``` - история коммитов  

### Удаленный репозиторий
- ```git remote add <имя (origin)> <SSH URL>``` - привязать удаленный репозиторий к локальному  
`-v` (без add) - проверить связь  
- ```git push``` - загрузить изменения в удаленный репозиторий  
Первый вызов с ключом -u, именем удаленного репозитория (origin) и названием текущей ветки (main/master)  
- ```git clone <SSH URL>``` - клонировать репозиторий  
Автоматически связывает удаленный и локальный репозитории