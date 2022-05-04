---
## Front matter
title: "Отчёт по лабораторной работе №6"
subtitle: "Дисциплина: Операционные системы"
author: "Подъярова Ксения Витальевна (группа: НПМбд-02-21)"

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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

# Выполнение лабораторной работы

1. Осуществляем вход в систему, используя свое имя пользователя.

2. Записываю в файл file.txt названия файлов, содержащиеся в каталоге /etc. Дописываю в этот же файл названия файлов, содержащиеся в домашнем каталоге.(рис. [-@fig:001])

![Файл file.txt](image/1.png){ #fig:001 width=70% }

3. Вывожу имена всех файлов из file.txt, имеющие расширение .conf, после чего записываю их в новый текстовой файл conf.txt.(рис. [-@fig:002])

![Файлы из file.txt, имеющие расширение .conf](image/2.png){ #fig:002 width=70% }

4. Определяю, какие файлы в домашнем каталоге имеют имена, начинающиеся с символа c. (рис. [-@fig:003]) (рис. [-@fig:004])

![Имена каталогов, начинающиеся с символа с](image/3.png){ #fig:003 width=70% }

![Имена каталогов, начинающиеся с символа с](image/4.png){ #fig:004 width=70% }

5. Вывожу на экран имена файлов из каталога /etc, начинающиеся с символа h.(рис. [-@fig:005])

![Имена каталогов, начинающиеся с символа h](image/5.png){ #fig:005 width=70% }

6. Запускаю в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log.(рис. [-@fig:006])

![Запуск фонового режима](image/6.png){ #fig:006 width=70% }

7. Удаляю файл ~/logfile.(рис. [-@fig:007])

![Удаление файла ~/logfile](image/7.png){ #fig:007 width=70% }

8. Запускаю из консоли в фоновом режиме редактор gedit.(рис. [-@fig:008]) (рис. [-@fig:009])

![Редактор gedit](image/8.png){ #fig:008 width=70% }

![Редактор gedit](image/9.png){ #fig:009 width=55% }

9. Читаю справку (man) команды kill, после чего использую её для завершения процесса gedit.(рис. [-@fig:010]) (рис. [-@fig:011])

![Команда man kill](image/10.png){ #fig:010 width=70% }

![Справка команды kill](image/11.png){ #fig:011 width=60% }

10. Выполняю команды df и du, предварительно получив более подробную информацию об этих командах, с помощью команды man.(рис. [-@fig:012]) (рис. [-@fig:013])

![Справка команды df](image/12.png){ #fig:012 width=70% }

![Справка команды du](image/13.png){ #fig:013 width=60% }

11. Воспользовавшись справкой команды find, вывожу имена всех директорий, имеющихся в домашнем каталоге(рис. [-@fig:014])

![Справка команды find](image/14.png){ #fig:014 width=60% }


# Выводы

Я ознакомилась с инструментами поиска файлов и фильтрации текстовых данных, приобрела практические навыки: по управлению процессами, по
проверке использования диска и обслуживанию файловых систем.


