[< к Оглавлению](/readme.md)
### Команда
**git init** - позволяет создать пустой репозиторий Git или повторно инициализировать существующий.

### Описание
Эта команда создает пустой репозиторий **Git** — по сути, .git каталог с подкаталогами для файлов objects, refs/heads, refs/tags и шаблонов. Будет создана начальная ветка без каких-либо коммитов.

### Пример

Создать новый GIT репозиторий по существующему коду:

    $ cd /path/to/my/codebase
    $ git init      (1)
    $ git add .     (2)
    $ git commit    (3)

 1. Создать каталог по прописанному пути;
 2. Добавить все существующие файлы в [индекс](/commands/add.md);
 3. Записать первый коммит.