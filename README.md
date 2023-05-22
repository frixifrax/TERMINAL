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

>Таким образом мы переместились на уровень выше из папки ~/folder_3/dir_1 в папку ~/folder_3

![](https://lh3.googleusercontent.com/drive-viewer/AFGJ81r6ivKvyi8Ait16ThoFu2eX7NE53056oGmvORK95IJZjoEz6_xttwP7bKJgN8sLsw-cVKxn2WGKX_ViPlL5GyRDK49bQg=s1600)
---

### 13) переместить любые 2 файла, которые вы создали, в любую другую папку.

### 14) скопировать любые 2 файла, которые вы создали, в любую другую папку.

### 15) Найти файл по имени

### 16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.

### 17) вывести несколько первых строк из текстового файла

### 18) вывести несколько последних строк из текстового файла

### 19) просмотреть содержимое длинного файла (команда less) изучите как она работает.

### 20) вывести дату и время

=========

## Задание *

### 1) Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request

### 2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

=====================
1) Посмотреть где я - pwd
2) Создать папку - mkdir foldername
3) Зайти в папку - cd foldername
