---
## Front matter
title: "Четвертый этап индивидуального проекта"
subtitle: "Добавление к сайту ссылки на научные и библиометрические ресурсы"
author: "Заболотная Кристина Александровна"

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

Научиться добавлять к сайту ссылки на научные и библиометрические ресурсы.

# Задание

1. Добавить к сайту ссылки на научные и библиометрические ресурсы. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте. 
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору:
а) Оформление отчёта.
б) Создание презентаций.
в) Работа с библиографией.

# Выполнение лабораторной работы

1. Необходимо добавить к сайту ссылки на научные и библиометрические ресурсы. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте. 

![сайты](image/эт40.png){#fig:001 width=90%}

2. Добавляем пост на тему по выбору: Оформление отчёта.

![пост по выбору](image/эт41.png){#fig:002 width=90%}

![пост по выбору](image/эт42.png){#fig:003 width=90%}

3. Добавляем пост по прошедшей неделе.

![пост о прошедшей неделе](image/эт43.png){#fig:004 width=90%}

![пост о прошедшей неделе](image/эт44.png){#fig:005 width=90%}

# Выводы

В ходе выполнения данной лабораторной работы (индивидуального проекта) я научилась добавлять к сайту ссылки на научные и библиометрические ресурсы.

# Список литературы{.unnumbered}

::: {#refs}
:::
