# Bash
Bash commands and scripts
### Посмотреть где я:
> pwd
### Создать папку (Test_Folder):
> mkdir Test_Folder
### Перейти в созданную папку :
> cd Test_Folder
### Создать 3 папки (F1, F2, F3):
> mkdir F1 F2 F3
### Зайти в любую папку(F2):
> cd F2
### Создать 5 файлов(text1.txt, text2.txt, text3.txt, json1.json, json2.json):
> touch text1.txt text2.txt text3.txt json1.json json2.json
### Создать 3 папки (Inner_Folder1, Inner_Folder2, InnerFolder3):
> mkdir Inner_Folder1 Inner_Folder2 InnerFolder3
### Вывести список содержимого папки:
> ls
### Открыть любой txt файл
#### написать туда что-нибудь, любой текст
#### сохранить и выйти
#### Выйти из папки на уровень выше
> cd ../
### Переместить 2 файла в другую папку
> mv "text1.txt,text2.txt" Inner_Folder1
### Скопировать любые 2 файла в любую другую папку
> cp json1.json
#!/bin/bash /
cd test
mkdir f1 f2 f3
cd f1
touch file1.txt file2.txt file3.txt json1.json json2.json
mkdir FoLdEr1 FoLdEr2 FoLdEr3
ls -la
mv {file1.txt,file2.txt} f2
