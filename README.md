# Bash
Bash commands and scripts
### 1) Посмотреть где я:
    pwd
### 2) Создать папку (Test_Folder):
    mkdir Test_Folder
### 3) Перейти в созданную папку :
     cd Test_Folder
### 4) Создать 3 папки (F1, F2, F3):
     mkdir F1 F2 F3
### 5) Зайти в любую папку(F2):
     cd F2
### 6) Создать 5 файлов(text1.txt, text2.txt, text3.txt, json1.json, json2.json):
     touch text1.txt text2.txt text3.txt json1.json json2.json
### 7) Создать 3 папки (Inner_Folder1, Inner_Folder2, InnerFolder3):
     mkdir Inner_Folder1 Inner_Folder2 InnerFolder3
### 8) Вывести список содержимого папки:
     ls
### 9) Открыть любой txt файл
     vim text1.txt
### 10) написать туда что-нибудь, любой текст
##### (Hello world!)
### 11) сохранить и выйти
##### Press ESC, then execute :wq
### 12) Выйти из папки на уровень выше
        cd ../
### 13) Переместить 2 файла в другую папку
        mv {text1.txt,text2.txt} Inner_Folder1
### 14) Скопировать любые 2 файла в любую другую папку
        cp {json1.json,json2.json} Inner_Folder2
### 15) Найти файл по имени
         find -name text3.txt
### 16) Просмотреть содержимое файла в реальном времени (text1.txt)
        tail -f Inner_Folder1/text1.txt
### 17) Вывести несколько первых строк из текстового файла (3)
         head -n 3 Inner_Folder1/text1.txt
### 18) Вывести несколько последних строк из текстового файла (2)
         tail -n 2 Inner_Folder1/text1.txt
### 19) Просмотреть содержимое длинного файла (War_and_Peace.txt)
#### Командой Less открываем файл War_and_Peace.txt в режиме постраничного просмотра
#### Перемещаемся между страницами с помощью Pg UP и Pg DOWN
#### Для выхода из режима просмотра нажать Q
         less War_and_Peace.txt
### 20) Отправить http запрос на сервер
#### http://162.55.220.72:5005/terminal-hw-request
         curl http://162.55.220.72:5005/terminal-hw-request
### 21) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
        
        #!/bin/bash /
        cd test
        mkdir f1 f2 f3
        cd f1
        touch file1.txt file2.txt file3.txt json1.json json2.json
        mkdir FoLdEr1 FoLdEr2 FoLdEr3
        ls -la
        mv {file1.txt,file2.txt} f2
