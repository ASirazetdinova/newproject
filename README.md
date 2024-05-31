## **Навигация**

`pwd` (***p**rint **w**orking **d**irectory)* — показать рабочую папку, узнать текущее местоположение 

`.` — текущая директория  

`..` — родительская директория

`~` — домашняя директория

`cd` (***c**hange **d**irectory*) — сменить директорию

`ls` (**l**i**s**t directory contents) — отобразить содержимое директории

`ls` с флагом `-a` — отображение расширенного списка со скрытыми файлами, которые начинаются с символа `.` (например, файлы конфигурации)

**macOS / Linux** — `/ + [Tab] + [Tab]` или `cd / + [Enter]` —содержимое корневой директории

**Windows** — `cd c:/ + [Enter]` или `cd /c + [Enter]` — перемещение в корневую директорию

`touch file_name.txt` — создать файл. Хорошей практикой при создании файла считается указать его расширение

`mkdir folder_name` (**m**a**k**e **dir**ectory) — создать директорию 

`mkdir -p dir1/dir-inside/dir-deeper-inside` — создать структуру директорий

`cp что_копируем куда_копируем` (**c**o**p**y) — копирование файлов

`mv что_переместить куда_переместить` (**m**o**v**e) — переместить файлы и папки

`cat file_name.txt` (c*on**cat**enate and print* ) — распечатать содержимое текстового файла 

`rm file_name` (**r**e**m**ove) — удалить файл

`rmdir folder_name` (**r**e**m**ove **dir**ectory) — удалить папку, если она пустая

`rm -r folder_name` (`-r` — **r**ecursive) — **рекурсивно** удаляет файлы и папки

`git config --global user.name` — установить имя/ник пользователя

`git config --global user.email` — установить почту пользователя

`cat ~/.gitconfig` или `git config --list` — способ проверки содержимого файла конфигурации

`git init` — инициализировать репозиторий

`rm -rf .git` — разгитить папку, если что-то пошло не так

`-r` (--**r**ecursive) - флаг/ключ, который позволяет удалять папки вместе с их содержимым

`-f` (--**f**orce) -флаг/ключ, который избавит вас от вопросов вроде «Вы точно хотите удалить этот файл?»

`git status` — проверить статус / состояние репозитория 

`git add --all` —  подготовить к сохранению **все** файлы в репозитории

`git add .` — добавить всю текущую папку вместе с ее содержимым

`git commit -m ’message’` — сделать коммит

`git log` (*log* — «журнал [записей]») — просмотреть историю коммитов

`ls -la .ssh/` — вывести список сгенерированных ключей

`ssh-keygen -t ed25519 -C 'email'` - сгенерировать ssh-ключ

`ls -a ~/.ssh` — проверка на наличие сгенерированной пары ssh-ключей

**macOS —** `pbcopy < ~/.ssh/id_rsa.pub` — копировать содержимое файла с публичным ключом в буфер обмена

**Windows —** `clip < ~/.ssh/id_rsa.pub` — копировать содержимое ключа в буфер обмена

`cat ~/.ssh/id_rsa.pub` или `cat ~/.ssh/id_ed25519.pub` - вывести содержимое файла с ключом

`ssh -T git@github.com` — проверить правильность ключа 

`git remote add [origin] [URL]` (*remote* — «удаленный») — привязать удаленный репозиторий к локальному

`git remote -v` — убедиться, что репозитории связаны

`-v` (`--verbose` «подробный») - флаг, который позволяет показать больше информации в выводе

`git push` — загрузить содержимое локального репозитория на GitHub

`git push -u origin main` - первая версия команды в случае работы с новым репозиторием
