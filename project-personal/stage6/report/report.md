---
## Front matter
title: "Отчёт по 6 этапу индивидуального проекта"
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

Размещение двуязычного сайта на Github.

# Задание


 * Сделать поддержку английского и русского языков.
 
 * Разместить элементы сайта на обоих языках.
 
 * Разместить контент на обоих языках.
    
 * Сделать пост по прошедшей неделе.
    
 * Добавить пост на тему по выбору.

# Выполнение 6 этапа индивидуального проекта

1. Создаю папку i18n в blog. Загружаю файл английского языка в папку i18n, чтобы был путь вида i18n/en.yaml. (рис. [-@fig:001] , [-@fig:002])

![Создание папки i18n](image/1.png){ #fig:001 width=55% }

![Файл английского языка](image/2.png){ #fig:002 width=55% }

2. Создаю в /blog/content 2 папки: en и ru. И копирую все файлы, которые содержались в content в эти папки (рис. [-@fig:003]).

![Создание ru и en](image/3.png){ #fig:003 width=55% }

3. В /blog/config/_default изменяю файл languages.yaml и добавляю 2 файла menus (рис. [-@fig:004] , [-@fig:005]))

![Добавление menus](image/4.png){ #fig:004 width=55% }

![languages.yaml](image/5.png){ #fig:005 width=55% }

4. Размещаю элементы сайта на обоих языках (рис. [-@fig:006], [-@fig:007], [-@fig:092] , [-@fig:091])

![Поддержка английского и русского языков](image/6.png){ #fig:006 width=55% }

![Размещение элементов сайта](image/7.png){ #fig:007 width=55% }

![Размещение элементов сайта](image/92.png){ #fig:092 width=55% }

![Размещение элементов сайта](image/91.png){ #fig:091 width=55% }

5. Размещаю контент на обоих языках (рис. [-@fig:008], [-@fig:042], [-@fig:041])

![Размещение контента](image/8.png){ #fig:008 width=55% }

![Размещение контента](image/42.png){ #fig:042 width=55% }

![Размещение контента](image/41.png){ #fig:041 width=55% }

6. Добавляю 2 поста: пост по прошедшей неделе и пост на тему "День защиты детей". Для этого в папке post создаю 2 новые папки и изменяю файл index.md (рис. [-@fig:009],  [-@fig:011])

![Добавление поста](image/555.png){ #fig:009 width=55% }

![Добавление поста](image/9.png){ #fig:011 width=55% }


# Выводы

Я научилась делать поддержку русского и английского языков


