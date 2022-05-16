# Linux-Commands-Cheat-Sheet
Linux Commands Cheat Sheet

## Основные команды терминала Linux

### Навигация

* **cd /.** - Переход в основной каталог
* **cd** - Переход в домашний каталог (переменная $HOME)
* **cd /root** - Переход в каталог /root
* **cd ..** - Переход на один уровень ниже
* **cd /root/.ssh** - Переход в скрытую папку .ssh

### Работа с файлами

* **ls** – Показывает файлы и каталоги в текущей папке
* **pwd** - Отображает текущий рабочий каталог
* **mkdir NewFolder** - Создает новый каталог с именем "NewFolder".
* **cat FileName** - Открывает файл FileName
* **nano FileName** - Открывает файл FileName (возможно потребуется утсновка nano)
* **rm NewFile** - Удаляет файл с именем "NewFile"
* **rm -f NewFile** - Принудительное удаление файла с именем "NewFile"
* **rm -r NewFolder** - Рекурсивно удаляет каталог с именем "NewFolder"
* **rm -rf NewFolder** - Принудительное удаление каталога с именем "NewFolder" рекурсивно
* **cp oldfile1 newfile2** - Копирует содержимое oldfile1 в newfile2
* **cp -r olddir1 newdir2** - Рекурсивно копирует каталог "olddir1" в "newdir2". Dir2 будет создан, если он не существует.
* **mv oldfile1 newfile2** - Переименовывает "oldfile1" в "newfile2".
* **ln -s /etc/log/file logfile** - Создает ярлык на файл
* **touch newfile** - Создает пустой файл с именем newfile
* **cat > newfile** - Помещает STDIN в newfile
* **more newfile** - Выводит содержимое newfile по частям
* **head newfile** - Выводит первые 10 строк файла newfile
* **tail newfile** - Вывод последних 10 строк newfile
