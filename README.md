# Bash
Bash commands and scripts
### Посмотреть где я:
    pwd
### Создать папку (Test_Folder):
    mkdir Test_Folder
### Перейти в созданную папку :
     cd Test_Folder
### Создать 3 папки (F1, F2, F3):
     mkdir F1 F2 F3
### Зайти в любую папку(F2):
     cd F2
### Создать 5 файлов(text1.txt, text2.txt, text3.txt, json1.json, json2.json):
     touch text1.txt text2.txt text3.txt json1.json json2.json
### Создать 3 папки (Inner_Folder1, Inner_Folder2, InnerFolder3):
     mkdir Inner_Folder1 Inner_Folder2 InnerFolder3
### Вывести список содержимого папки:
     ls
### Открыть любой txt файл
     vim text1.txt
### написать туда что-нибудь, любой текст
##### (Hello world!)
### сохранить и выйти
##### Press ESC, then execute :wq
### Выйти из папки на уровень выше
        cd ../
### Переместить 2 файла в другую папку
     mv {text1.txt,text2.txt} Inner_Folder1
### Скопировать любые 2 файла в любую другую папку
        cp {json1.json,json2.json} Inner_Folder2
### Найти файл по имени
         find -name text3.txt
### Просмотреть содержимое файла в реальном времени (text1.txt)
        tail -f Inner_Folder1/text1.txt
### Вывести несколько первых строк из текстового файла (3)
         head -n 3 Inner_Folder1/text1.txt
### Вывести несколько последних строк из текстового файла (2)
         tail -n 2 Inner_Folder1/text1.txt
### Просмотреть содержимое длинного файла (War_and_Peace.txt)
#### Командой Less открываем файл War_and_Peace.txt в режиме постраничного просмотра
#### Перемещаемся между страницами с помощью Pg UP и Pg DOWN
#### Для выхода из режима просмотра нажать Q
         less War_and_Peace.txt
### Отправить http запрос на сервер
#### http://162.55.220.72:5005/terminal-hw-request
         curl http://162.55.220.72:5005/terminal-hw-request
###  Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
        
        #!/bin/bash /
        cd test
        mkdir f1 f2 f3
        cd f1
        touch file1.txt file2.txt file3.txt json1.json json2.json
        mkdir FoLdEr1 FoLdEr2 FoLdEr3
        ls -la
        mv {file1.txt,file2.txt} f2
