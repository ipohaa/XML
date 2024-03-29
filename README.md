### Домашнее задание на тему GitHub
Работа с файловой системой Git, ознакомление с XML  
+ [1. Создать внешний репозиторий c названием XML](https://github.com/ipohaa/XML#1-создать-внешний-репозиторий-c-названием-xml)
+ [2. Клонировать репозиторий XML на локальный компьютер](https://github.com/ipohaa/XML#2-клонировать-репозиторий-xml-на-локальный-компьютер)
+ [3. Внутри локального XML создать файл "new.xml"](https://github.com/ipohaa/XML#3-внутри-локального-xml-создать-файл-newxml)
+ [4. Добавить файл под гит](https://github.com/ipohaa/XML#4-добавить-файл-под-гит)
+ [5. Закоммитить файл](https://github.com/ipohaa/XML#5-закоммитить-файл)
+ [6. Отправить файл на внешний GitHub репозиторий](https://github.com/ipohaa/XML#6-отправить-файл-на-внешний-github-репозиторий)
+ [7. Отредактировать содержание файла "new.xml"](https://github.com/ipohaa/XML#7-отредактировать-содержание-файла-newxml)
+ [8. Отправить изменения на внешний репозиторий](https://github.com/ipohaa/XML#8-отправить-изменения-на-внешний-репозиторий)
+ [9. Создать файл preferences.xml](https://github.com/ipohaa/XML#9-создать-файл-preferencesxml)
+ [10. В файл preferences.xml добавить информацию о своих предпочтениях в формате XML](https://github.com/ipohaa/XML#10-в-файл-preferencesxml-добавить-информацию-о-своих-предпочтениях-в-формате-xml)
+ [11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML](https://github.com/ipohaa/XML#11-создать-файл-skillsxml-добавить-информацию-о-скиллах-которые-будут-изучены-на-курсе-в-формате-xml)
+ [12. Отправить сразу 2 файла на внешний репозиторий](https://github.com/ipohaa/XML#12-отправить-сразу-2-файла-на-внешний-репозиторий)
+ [13-14. На веб интерфейсе создать файл bug_report.xml и сделать commit](https://github.com/ipohaa/XML#13-14-на-веб-интерфейсе-создать-файл-bug_reportxml-и-сделать-commit-сохранить)
+ [15-16. На веб интерфейсе модифицировать файл bug_report.xml и сделать commit](https://github.com/ipohaa/XML#15-16-на-веб-интерфейсе-модифицировать-файл-bug_reportxml-добавить-баг-репорт-в-формате-xml-и-сделать-commit-сохранить)
+ [17. Синхронизировать внешний и локальный репозиторий XML](https://github.com/ipohaa/XML#17-синхронизировать-внешний-и-локальный-репозиторий-xml)

## 1. Создать внешний репозиторий c названием XML.
+ Зайти и авторизоваться на сайте
+ Нажать `New repositories`
+ Ввести имя нового репозитория в поле `Repository name`
+ Нажать `Create repository`

## 2. Клонировать репозиторий XML на локальный компьютер.
```console
Ipohaa@MainPC MINGW64 /f/git
$ git clone https://github.com/<имя>/XML.git
```
## 3. Внутри локального XML создать файл "new.xml".
```console
Ipohaa@MainPC MINGW64 /f/git/XML (main)
$ cat > new.xml
```
## 4. Добавить файл под гит.
Так как мы создали новый файл и гит о нём не знает, его нужно индексировать, воспользуемся `git add <файл>` чтобы добавить новый файл
```console
Ipohaa@MainPC MINGW64 /f/git/XML (main)
$ git add new.xml
```
## 5. Закоммитить файл. 
Синтаксис коммита `git commit -m "Описание коммита"`
```console
$ git commit -m "Add new file new.xml"
```
## 6. Отправить файл на внешний GitHub репозиторий.
```console
$ git push
```
## 7. Отредактировать содержание файла "new.xml"
Написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата) в формате XML.
```console
Ipohaa@MainPC MINGW64 /f/git/XML (main)
$ vi new.xml
```
## 8. Отправить изменения на внешний репозиторий.
Закоммитим наши изменения
```console
$ git commit -am "Update file new.xml"
```
и отправим на внешний репозиторий
```console
$ git push
```
## 9. Создать файл preferences.xml
```console
Ipohaa@MainPC MINGW64 /f/git/XML (main)
$ cat > preferences.xml
```
## 10. В файл preferences.xml добавить информацию о своих предпочтениях в формате XML.
```console
Ipohaa@MainPC MINGW64 /f/git/XML (main)
$ vi preferences.xml
```
## 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```console
Ipohaa@MainPC MINGW64 /f/git/XML (main)
$ cat > skills.xml
```
## 12. Отправить сразу 2 файла на внешний репозиторий.
Закоммитим наши изменения
```console
$ git commit -m "Add new file preferences.xml and skills.xml"
```
и отправим на внешний репозиторий
```console
$ git push
```
## 13-14. На веб интерфейсе создать файл bug_report.xml и сделать commit (сохранить).
+ Создадим новый файл `Add file` -> `Create new file`
+ Назовём файл bug_report.xml
+ Сохраним файл, выберем `Commit new file`
## 15-16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML и сделать commit (сохранить).
Чтобы редактировать файл, нам нужно его выбрать, нажав на его имя в списке
+ Выбираем файл bug_report.xml
+ Выбираем пиктограмму карандаша `Edit this file`
+ Редактируем в нужном для нас формате
+ Сохраняем -> `Commit changes`

## 16. Синхронизировать внешний и локальный репозиторий XML
Воспользуемся `git pull` для того чтобы синхронизировать файлы из внешнего репозитория на локальном компьютере
```console
Ipohaa@MainPC MINGW64 /f/git/XML (main)
$ git pull
```
