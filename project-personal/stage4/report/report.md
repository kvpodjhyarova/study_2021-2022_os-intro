---
## Front matter
title: "Отчёт по 4 этапу индивидуального проекта"
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

Добавить к сайту ссылки на научные и библиометрические ресурсы. Cделать 2 поста.

# Задание

1. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:

  * eLibrary

  * Google Scholar

  * ORCID

  * Mendeley

  * ResearchGate

  * Academia.edu

  * arXiv

  * github

2. Сделать пост по прошедшей неделе.

3. Добавить пост на тему по выбору:

  * Оформление отчёта.
  
  * Создание презентаций.
  
  * Работа с библиографией.


# Выполнение 4 этапа индивидуального проекта

1. Регистрируюсь на соответствующих ресурсах и размещаю на них ссылки на сайте, изменив файл index.md в /blog/content/authors/admin (рис. [-@fig:001]) (рис. [-@fig:002])

![Добавление ссылок на ресурсы](image/1.png){ #fig:001 width=55% }

![Размещение ссылок на сайте](image/2.png){ #fig:002 width=55% }

2. Добавляю пост по прошедшей неделе. Для этого в папке post создаю новую папку "Post4" и изменяю файл index.md (рис. [-@fig:003]) (рис. [-@fig:004])

![Добавление поста по прошедшей неделе](image/3.png){ #fig:003 width=55% }

![Добавление поста по прошедшей неделе](image/4.png){ #fig:004 width=55% }

4. Добавляю пост на тему "". Для этого в папке post создаю новую папку "Post5" и изменяю файл index.md (рис. [-@fig:005]) (рис. [-@fig:006])

![Добавление поста на тему "Оформление отчёта"](image/5.png){ #fig:005 width=55% }

![Добавление поста на тему "Оформление отчёта"](image/6.png){ #fig:006 width=55% }

# Выводы

Я научилась добавлять к сайту ссылки на научные и библиометрические ресурсы.


