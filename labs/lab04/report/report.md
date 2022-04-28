---
## Front matter
title: "Отчет по лабораторной работе №4"
subtitle: "дисциплина: Операционные системы"
author: "Подъярова Ксения Витальевна (НПМбд-02-21)"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.


# Выполнение лабораторной работы

1. Определяем полное имя домашнего каталога с помощью команды pwd (рис. [-@fig:001])

!["Полное имя домашнего каталога](image/1.png){ #fig:001 width=70% }


2. Выполним действия:	

1) Переходим в каталог /tmp. Выводим на экран содержимое каталога/tmp.Для этого используем команду ls с различными опциями.

"ls" - выводится список каталогов и файлов, которые можно увидеть, "вручную" открыв каталог tmp (рис. [-@fig:021])

!["Команда "ls"](image/21.png){ #fig:021 width=70% }

"ls -a"  - к списку, описанному в предыдущем пункте, добавляются скрытые каталоги и файлы (рис. [-@fig:022])

!["Команда "ls -а"](image/22.png){ #fig:022 width=70% }

"ls -F" - с помощью этой команды получаем информацию о типах файлов (рис. [-@fig:023])

!["Команда "ls -F"](image/23.png){ #fig:023 width=70% }

"ls -l" - получаем список каталогов и файлов, но уже с более подробной информацией о них (рис. [-@fig:024])

!["Команда "ls -l"](image/24.png){ #fig:024 width=70% }

"ls -alF" - данная команда отображает список всех каталогов и файлов, в том числе и скрытых, с подробной информацией о них (рис. [-@fig:025])

!["Команда "ls -alF"](image/25.png){ #fig:025 width=57% }

2) Определяем ,есть ли в каталоге /var/spool подкаталог с именем cron (рис. [-@fig:026])

!["Каталог /var/spool"](image/26.png){ #fig:026 width=70% }

3) Переходим в домашний каталог и выводим на экран его содержимое (рис. [-@fig:027])

!["Вывод на экран содержимого домашнего каталога"](image/27.png){ #fig:027 width=70% }



3. Выполним действия:
1) В домашнем каталоге создаем новый каталог с именем newdir. В каталоге ~/newdir создаем новый каталог с именем morefun (рис. [-@fig:031])

!["Создание каталога ~/newdir/morefun"](image/31.png){ #fig:031 width=70% }

2) В домашнем каталоге создаем одной командой три новых каталога с именами letters, memos, misk. Затем удаляем эти каталоги одной командой.(рис. [-@fig:032])

!["Создание и удаление трех новых каталогов с именами letters, memos, misk"](image/32.png){ #fig:032 width=70% }

3) Попробуем удалить ранее созданный каталог ~/newdir командой rm. Он не удалён.(рис. [-@fig:033])

!["Попытка удалить каталог ~/newdir"](image/33.png){ #fig:033 width=70% }

4) Удаляем каталог ~/newdir/morefun из домашнего каталога. Проверяем, был ли каталог удалён. (рис. [-@fig:034])

!["Удаляем каталог ~/newdir"](image/34.png){ #fig:034 width=70% }


4. С помощью команды man определяем, какую опцию команды ls нужно использовать для просмотра содержимого не только указанного каталога, но и подкаталогов, входящих в него.(рис. [-@fig:004])

!["Определение опции команды ls"](image/4.png){ #fig:004 width=70% }


5. С помощью команды man определите опцию команды ls, позволяющую отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов.(рис. [-@fig:005])

!["Определение опции команды ls"](image/5.png){ #fig:005 width=70% }


6. Используем команду man для просмотра описания следующих команд:cd,pwd,mkdir,rmdir,rm.

1) Описание команды сd (рис. [-@fig:061])

!["Описание команды сd"](image/61.png){ #fig:061 width=70% }

2) Описание команды pwd (рис. [-@fig:062])

!["Описание команды pwd"](image/62.png){ #fig:062 width=70% }

3) Описание команды mkdir (рис. [-@fig:063])

!["Описание команды mkdir"](image/63.png){ #fig:063 width=70% }

4) Описание команды rmdir (рис. [-@fig:064])

!["Описание команды rmdir"](image/64.png){ #fig:064 width=70% }

5) Описание команды rm (рис. [-@fig:065])

!["Опции команды rm "](image/65.png){ #fig:065 width=70% }


7. Выведем историю команд с помощью команды "history" (рис. [-@fig:007])

!["Вывод истории команд "](image/7.png){ #fig:007 width=70% }

# Выводы

Я приобрела практические навыки взаимодействия пользователя с системой посредством командной строки.


