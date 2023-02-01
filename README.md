# Instruction for Git
**git config --list** - проверка используемой конфигурации

**git config user.name** - имя пользователя

**git config user.mail** - почта пользователя

**git status** - данные о статусе пользователя

**git add file_name/git add .**  -  добавление в индекс отслеживания файла

**git commit -m "commit_message"** - фиксация изменений в файле
- -m (message) - сообщение
- -am (let us avoid repeating command add) - *исключение повторений команды add с помощью  - am, где a- команда add, m-сообщение*

**git log** - проверка повторений

**git checkout 1234 [numbers]** - переключение между коммитами [хэш коммита]

**git checkout [master]**- переключение между ветками [ветка мастер]

**git diff** - показ изменений в файле

**git branch [test_branch]** - создание ветки [имя ветки]

**git branch** - показ ветки

**git checkout -b [name branch]** - одновременное создание новой ветки и переход в нее

**git merge [name branch]** - слияние веток [имя ветки, которую сливаем]

**git reset --merge ORIG_HEAD** -отмена слияния с последней веткой

**git add.gitignore** - автоматически исключает добавление файлов в репозиторий, а также исключает файлы из списка неотслеживаемых

**git log --graph** - визуализация веток и коммитов

# Работа с удаленным репозиторием

**git push** - добавляет изменения с локального репозитория на удаленный

**git pull** - добавляет изменения с удаленного репозитория на локальный

**git clone [адрес ссылки Github]**  - клонирование проекта с удаленного репозитория

**git init**- создает новый репозиторий Git. С ее помощью можно преобразовать существующий проект без управления версиями в репозиторий Git или инициализировать новый пустой репозиторий.

**git remote add [имя] [url-адрес]**-добавление удалённого репозитория

**git fetch** - Данная команда связывается с указанным удалённым проектом и забирает все те данные проекта, которых  ещё нет