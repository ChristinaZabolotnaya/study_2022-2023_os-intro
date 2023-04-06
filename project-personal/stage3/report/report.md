---
## Front matter
title: "Третий этап индивидуального проекта"
subtitle: "Добавление к сайту достижений"
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

Научиться добавлять к сайту достижения, список достижений (о навыках (Skills), об опыте (Experience), о достижениях (Accomplishments)).

# Задание

Добавить к сайту достижения.

1. Список достижений.
   а) Добавить информацию о навыках (Skills).
   б) Добавить информацию об опыте (Experience).
   в) Добавить информацию о достижениях (Accomplishments).
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору:
   а) Легковесные языки разметки.
   б) Языки разметки. LaTeX.
   в) Язык разметки Markdown.


# Выполнение лабораторной работы

1. Необходимо добавить к сайту достижения. Начинаем с skills.

![skills](image/эт31.png){#fig:001 width=90%}

2. Добавляем Experience.

![Experience](image/эт32.png){#fig:002 width=90%}

3. Добавляем Accomplishments.

![Accomplishments](image/эт33.png){#fig:003 width=90%}

4. Каким образом все это выглядит на сайте.
 
![сайт] (image/эт34.png){#fig:004 width=90%}

5. Добавляем пост по прошедшей неделе.

![пост о прошедшей неделе](image/эт35.png){#fig:005 width=90%}

![пост о прошедшей неделе](image/эт36.png){#fig:006 width=90%}

6. Добавляем пост по одной из предложенных тем. Я выбрала - язык разметки Markdown.

![Markdown](image/эт37.png){#fig:007 width=90%}

![Markdown](image/эт38.png){#fig:008 width=90%}

7. Сам сайт с blog.

![сайт](image/эт39.png){#fig:009 width=90%}

# Выводы

В ходе выполнения данной лабораторной работы (индивидуального проекта) я научилась добавлять к сайту достижения.

# Список литературы{.unnumbered}

::: {#refs}
:::
