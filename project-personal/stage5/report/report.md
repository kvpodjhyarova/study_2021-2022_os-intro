---
## Front matter
title: "Отчёт по 5 этапу индивидуального проекта"
subtitle: "Дисциплина: Операционные системы"
author: "Подъярова Ксения Витальевна"

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

Добавить к сайту все остальные элементы. Cделать 2 поста.

# Задание

1. Сделать записи для персональных проектов.

2. Сделать пост по прошедшей неделе.

3. Добавить пост на тему "Языки научного программирования".


# Выполнение 5 этапа индивидуального проекта

1. Создаю запись для персонального проекта, изменив файл index.md в /blog/content/project (рис. [-@fig:001]) (рис. [-@fig:002])

![Создание записи для персоального проекта](image/1.png){ #fig:001 width=55% }

![Размещение проекта на сайте](image/2.png){ #fig:002 width=55% }

2. Добавляю пост по прошедшей неделе. Для этого в папке post создаю новую папку "Post6" и изменяю файл index.md (рис. [-@fig:003]) (рис. [-@fig:004])

![Добавление поста по прошедшей неделе](image/3.png){ #fig:003 width=55% }

![Добавление поста по прошедшей неделе](image/4.png){ #fig:004 width=55% }

3. Добавляю пост на тему "Языки научного программирования". Для этого в папке post создаю новую папку "Post7" и изменяю файл index.md (рис. [-@fig:005]) (рис. [-@fig:006])

![Добавление поста на тему "Языки научного программирования"](image/5.png){ #fig:005 width=55% }

![Добавление поста на тему "Языки научного программирования"](image/6.png){ #fig:006 width=55% }

# Выводы

Я научилась делать записи для персональных компьютеров.


