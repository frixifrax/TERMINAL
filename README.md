# Terminal homework#1
##### Первое домашнее задание Linux terminal (GitBash) commands
---

### 1) Посмотреть где я
`pwd`

Для того, чтобы узнать где мы находимся, воспользуемся командой `pwd` сокращение от *print working directory*


>Результатом будет отображение пути `/c/Users/0x`

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81plohVDVUODgCF0XacFvOTJ1hcSVLY_8mRBhC0p7GqxRk4lm7Qh3CZNNszdc3FmumvBVRU0l9YYystCZ8BqF-FhlGrIXw=s1600)
---
### 2) Создать папку
`mkdir -v folder_3`

За создание папки отвечает команда `mkdir` от *make directory*. Для более наглядного отображения воспользуемся ключем `-v`, **--verbose**, который отображает сообщение о создании для каждой созданной папки

>Результатом будет создание папки folder_3, а также отображение подтверждающего сообщения, о её создании

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81rfLTTfCLupwbSmO8nXex0xVhUgFQYm5Mxh0zPVMQf00Jd8uAfXH0Is-vaM2OSuvN-JIkPAT2jdgRGCaLASILGWZ0gTpA=s1600)
---

### 3) Зайти в папку
`cd folder_3`

Используем команду `cd` от *change directory*

>В окне терминала сменилась рабочая папка и теперь отображается как **~/folder_3**

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81qU-PRAJPDeOcb34Vxy5PZrivpxARCka9l8Rw874ZC95rNN48f3uBdW6q1nAAJbNHsObCBKySykDlb5yNeJEPFEMjOK=s1600)
---

### 4) Создать 3 папки

`mkdir -v dir_1 dir_2 dir_3` 

>Создали три папки внутри **folder_3** и результат отобразился в окне терминала

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81qX4qxVtLgIp405Ev_dEd6ccVQ3-zyDIQzTtY-8ZOYiAos4JXX6dLV-nb80BsVXIyDVlNSfJp2jCyj4n5yVj5zLy6XGzw=s1600)
---

### 5) Зайти в любоую папку

`cd dir_1`

>Зашли в папку **dir_1**

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81otl9nbLgMka9LqwIrYDirI99Luab-opQ01C-h1sQAy79pzIMzmjQ7NtJUMXREyuIIcXeYnZ-QZUJyEuoN5bV48YMwKjQ=s1600)
---

### 6) Создать 5 файлов (3 txt, 2 json)

`touch file1.txt file2.txt file3.txt file4.json file5.json`

> Создали пять файлов file1.txt file2.txt file3.txt file4.json file5.json используя команду touch

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81pDIVe0kcUIJpuIk6kuCtQYslvsuHq8-oTW8Q1i0IqkdZzASK-bMKuS9siuILWDmUQep1y9ZqNtRq-G17VTsbZrX4LcUw=s1600)
---

### 7) Создать 3 папки

`mkdir -v fld1 fld2 fld3`

> Создали три папки fld1 fld2 fld3

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81o3syKo0DIUKrF9cTxnzdwVogIZpWpxKQaRnN0o3xu7JApMRzmv_xyWVO9_SIBUmDRsbWXK23fIRAE1rEcnXARsyIL9cw=s1600)
---

### 8. Вывести список содержимого папки

`ls -la`

Для вывода списка файлов и папок используем команду `ls`, при этом используем ключи `-a` для отображения всех файлов и папок в том числе скрытых, а также параметр `-l` для вывода данных в формате длинного списка

> Система отображает содержимое папки **dir1** в том числе скрытые файлы и папки в формате длинного списка

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81ridiyreFidp_W7k7vs6v5YDe4D076dIeirF5nFKzjxXRb4jVUNV2Bzmw_VSq4H2LyxMLLNBsWHRa0_YTXvfVK7AUph=s1600)
---

### 9) + Открыть любой txt файл

`vim file1.txt`

Воспользуемся редактором Vim.

> Окно терминала отображает открытый текстовой файл, доступный для редактирования

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81pCI9LuPNYfPyr2vfQXMgKpEIrums9n5f3rmdh84W0hqg3dnIeIxo7LIS0n5jJh1CCg1tX8mKagYHbLQBB1FM4Tc5OY=s1600)
---

### 10) + написать туда что-нибудь, любой текст.
Наберем в редакторе какой-нибудь текст

>Hello world!

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81qpwEl5d5W6rjxhykXRIrD_y56ist8PphixHcP7n1nbzhub0RfB7ZE-lhRbHuWMUoNPbQr4fGLW3rV18XLPIB_cg2Favw=s1600)
---

### 11) + сохранить и выйти.

Для сохранения файла с изменениями воспользуемся `Esc` + `:` + `w` + `q` + `Enter`

>Файл сохранён

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81p4rhLd4RDP_rKzCuWp1eQHIENtRCGrEz7DKquhISoaCsg22qw5uPUP4uG8gSkeph5F-hGfpsyirpDkx3tZN7MyYaC59A=s1600)
---

### 12) Выйти из папки на уровень выше

Для того, чтобы подняться на уровень выше используем команду `cd ..`

>Таким образом мы переместились на уровень выше из папки `~/folder_3/dir_1` в папку `~/folder_3`

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81r6ivKvyi8Ait16ThoFu2eX7NE53056oGmvORK95IJZjoEz6_xttwP7bKJgN8sLsw-cVKxn2WGKX_ViPlL5GyRDK49bQg=s1600)
---

### 13) переместить любые 2 файла, которые вы создали, в любую другую папку.

Перейдём в папку `dir_1`, где находятся созданные файлы. `cd dir_1`. Для перемещения файлов воспользуемся командой `mv` от анг **move** и переместим file2.txt и file3.txt в папку fld1
`mv -v file2.txt file3.txt fld1`

>Благодаря ключу -v --verbose можно видеть подтверждение перемещения файлов

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81pJqKTdgeMjB6pKQs3rSUmJt9CH0RDwjmbo8gKys5zQTG4nLXwFV8Dp2jEZKA-CFtXS03voCHTkC2zSoFPJAJEsIqvF7Q=s1600)

### 14) скопировать любые 2 файла, которые вы создали, в любую другую папку.

Для копирования используем команду `cp` от **copy**
`cp -v file4.json file5.json fld2`

> Файлы скопированы с подтверждением

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81qVkUbqrtzdo0zXOmppoB7tZelNmOD1yVmqKjQBT4XJ9v-HCoVacDKTphwJc82_VGfAerJpG9Nis603xEp1QvPvl7Hetw=s1600)

### 15) Найти файл по имени

Для поиска файла используем команду `find`. При этом указываем где искать и что искать. При поиске в текущей папке и ниже используем обозначение текущей директории `.`. Будем искать по имени файла, ключ `-name`. Допустим, нужно найти файл в имени которого присутствует цифра "4". Для этого используем маску `"*4*"`

> В результате отображается запрос по выдаче: найдены все файлы, в имени которые присутствует символ "4". Как видно поиске был произведен, не только в текущей папке, но и во вложенных папках также.

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81pgoZEpdGrJc76tDzn6h1Bu5nEPH6vPERZSIuTezo8yhnRyV_pbmfg2QnfAxpH4Hts8pMiIAmUqVK1VhJTyaecGbC15Fw=s1600)

### 16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.

Для просмотра содержимого файла в реальном времени существует команда 'tail -f'. Ключ `-f` используется для режима `follow` следование. Это значит, что после окончания чтения файла tail не будет остановлен, а будет ожидать дальнейший ввод текста для отображения. Так можно посмотреть содержимое десяти последних строчек файла. Для примера изменим файл file1.txt  и добавим туда в каждую строчку текст Hello worldN!, где N - это номер строки. Всего будет создано 12 строк.

> Команда tail -f отображает содержимое файла.

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81qjYEsQDLDyCjlv4URhhMAYIN5pfPiE6Tcoszl2fByUtj7PYVynI610YE64Gq8NGc-sHrXZTBL3h8nNr72URtqvDcFLPA=s1600)

> Теперь добавим ещё три строчки в файл и сохраним файл. При этом с помощью tail -f мы мгновенно увидим, что файл обновился и появились дополнительные строчки текста.

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81rVRIevWY2mwX4bLiZtSnRQbsQd4chaEfHQ20Sp2CT2TUii4nDKF4ebwbsk2IlGwv97L7Aa2YVqH7RaCCrF19iKy9wy=s1600)

> Для выхода из `tail -f` воспользуемся `Ctrl+c`. 
> Стоит заметить что команда grep используется для поиска текста внутри файлов. При этом используется синтаксис `grep *что_ищем* *имя_файла_где_ищем*`
> Например найдем world13 в файле file1.txt. Для этого воспользуемся командой `grep world13 file1.txt`

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81rKm4USyumhIqQbrQPYQ8pGTgI8DY7ndscm-B_DN9mTowVZkyvyNLFS9iyx9SZ3Y_c3Ofqqf_-U6PeuI-ifDdz0ZJKqDA=s1600)

### 17) вывести несколько первых строк из текстового файла

Для вывода первых строк текстового файла воспользуемся командой head -n X (где X количество строк для вывода). Выведем первые 7 строк, используя команду `head -n 7 file1.txt`

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81qzAkdNXi8_Tnv-TAVl-RhA3yLDprL3EreEcegn1H5l6OglrRowR04O0QkbZ60EgL2SYOwUq0wFMquQDzcBTm-g1inm=s1600)

### 18) вывести несколько последних строк из текстового файла

Чтобы вывести несколько последних строк текстового файла воспользуемся командой `tail -n X` (где X количество строк для вывода). Выведем последние 6 строк, используя команду `tail -n 6 file1.txt`

>0x@HOME-PC MINGW64 ~/folder_3/dir_1
>$ tail -n 6 file1.txt
>Hello world10!
>Hello world11!
>Hello world12!
>Hello world13!
>Hello world14!
>Hello world15!

![]()
### 19) просмотреть содержимое длинного файла (команда less) изучите как она работает.

Ппоместим большой текстовой файл setupact.log в директорию ~/folder_3/dir_1
Находясь в папке ~/folder_3/dir_1 воспользуемся командой `less setupact.log`. Теперь мы имеем возможность просматривать этот файл. Для перемщения удобно использовать хоткеи: `g` перемещает в начало файла; `G` перемещает в конец файла; `q` - для выхода из режима просмотра
![]()
### 20) вывести дату и время

Дата и время выводятся командой `date`

![]()
=========

## Задание *

### 1) Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request

### 2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

=====================
1) Посмотреть где я - pwd
2) Создать папку - mkdir foldername
3) Зайти в папку - cd foldername
