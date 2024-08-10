#Навигация

**pwd** (от англ. print working directory, «показать рабочую папку») — покажи, в какой я папке;
**ls** (от англ. list directory contents, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;
**ls -a** — покажи также скрытые файлы и папки, названия которых начинаются с символа .;
**cd ..** — перейди на уровень выше, в родительскую папку;
**cd ~** — перейди в домашнюю директорию (/Users/Username);
**cd /** — перейди в корневую директорию.

##Работа с файлами и папками

###Создание
**touch** index.html (англ. touch, «коснуться») — создай файл index.html в текущей папке;
**touch** index.html style.css script.js — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;
**mkdir** second-project (от англ. make directory, «создать директорию») — создай папку с именем second-project в текущей папке.

####Копирование и перемещение

**cp** file.txt ~/my-dir (от англ. copy, «копировать») — скопируй файл в другое место;
**mv** file.txt ~/my-dir (от англ. move, «переместить») — перемести файл или папку в другое место.

#####Чтение

**cat** file.txt (от англ. concatenate and print, «объединить и распечатать») — распечатай содержимое текстового файла file.txt.

######Удаление

**rm** about.html (от англ. remove, «удалить») — удали файл about.html;
**rmdir** images (от англ. remove directory, «удалить директорию») — удали папку images;
**rm -r** second-project (от англ. remove, «удалить» + recursive, «рекурсивный») — удали папку second-project и всё, что она содержит.

*База при работе с GitHub*

#Инициализация репозитория
**git init** (от англ. initialize, «инициализировать») — инициализируй репозиторий.

##Подготовка файла к коммиту
git add todo.txt (от англ. add, «добавить») — подготовь файл todo.txt к коммиту;
git add --all (от англ. add, «добавить» + all, «всё») — подготовь к коммиту сразу все файлы, в которых были изменения, и все новые файлы;
git add . — подготовь к коммиту текущую папку и все файлы в ней.

###Создание коммита
**git commit -m "Комментарий к коммиту."** (от англ. commit, «совершать», «фиксировать» + message, «сообщение») — сделай коммит и оставь комментарий, чтобы было проще понять, какие изменения внесены. 

####Просмотр информации о коммитах
**git log** (от англ. log, «журнал [записей]») — выведи подробную историю коммитов.

#####Просмотр состояния файлов
**git status** (от англ. status, «статус», «состояние») — покажи текущее состояние репозитория.