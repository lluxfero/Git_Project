# Шпаргалка. Базовые команды в консоли
## Навигация
- **pwd** (от англ. print working directory, «показать рабочую папку») — покажи, в какой я папке;<br>
- **ls** (от англ. list directory contents, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;<br>
- **ls -a** — покажи также скрытые файлы и папки, названия которых начинаются с символа .;<br>
- **cd first-project** (от англ. change directory, «сменить директорию») — перейди в папку first-project;<br>
- **cd first-project/html** — перейди в папку html, которая находится в папке first-project;<br>
- **cd ..** — перейди на уровень выше, в родительскую папку;<br>
- **cd ~** — перейди в домашнюю директорию (/Users/Username);<br>
- **cd /** — перейди в корневую директорию.<br>
## Работа с файлами и папками
### Создание
**touch index.html** (англ. touch, «коснуться») — создай файл index.html в текущей папке;<br>
**touch index.html style.css script.js** — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;<br>
**mkdir second-project** (от англ. make directory, «создать директорию») — создай папку с именем second-project в текущей папке.<br>
### Копирование и перемещение
**cp file.txt ~/my-dir** (от англ. copy, «копировать») — скопируй файл в другое место;<br>
**mv file.txt ~/my-dir** (от англ. move, «переместить») — перемести файл или папку в другое место.<br>
### Чтение
**cat file.txt** (от англ. concatenate and print, «объединить и распечатать») — распечатай содержимое текстового файла file.txt.<br>
### Удаление
**rm about.html** (от англ. remove, «удалить») — удали файл about.html;<br>
**rmdir images** (от англ. remove directory, «удалить директорию») — удали папку images;<br>
**rm -r second-project** (от англ. remove, «удалить» + recursive, «рекурсивный») — удали папку second-project и всё, что она содержит.<br>
## Полезные возможности
1.  Команды необязательно печатать и выполнять по очереди. Можно указать их списком — разделить двумя амперсандами (&&).<br>
2.  У консоли есть собственная память — буфер с несколькими последними командами. По ним можно перемещаться с помощью клавиш со стрелками вверх (↑) и вниз (↓).<br>
3.  Чтобы не вводить название файла или папки полностью, можно набрать первые символы имени и дважды нажать Tab. Если файл или папка есть в текущей директории, командная строка допишет путь сама. Например, вы находитесь в папке dev. Начните вводить cd first и дважды нажмите Tab. Если папка first-project есть внутри dev, командная строка автоматически подставит её имя. Останется только нажать Enter.<br>
