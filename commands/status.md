[< к Оглавлению](/readme.md)
### Команда
**git status** - Показать статус репозитория.

### Описание
Отображает пути, которые имеют различия между файлом индекса и текущей фиксацией HEAD, пути, которые имеют различия между репозиторием и файлом индекса, а также пути в рабочем дереве, которые не отслеживаются Git (и не игнорируются [gitignore](gitignore.md)). Первые — это то, что вы зафиксируете , запустив [git commit](/commands/commit.md); второе и третье — это то, что вы можете зафиксировать, запустив [git add](/commands/add.md) перед запуском git commit.

### Пример

Показать статутс в сокращенном формате:

    git status -s