---
## Front matter
title: "Лабораторная работа №14"
subtitle: "Именованные каналы"
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
  - \usepackage{float} # keep1. 
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Приобретение практических навыков работы с именованными каналами.

# Задание

Изучите приведённые в тексте программы server.c и client.c. Взяв данные примеры за образец, напишите аналогичные программы, внеся следующие изменения:
1. Работает не 1 клиент, а несколько (например, два).
2. Клиенты передают текущее время с некоторой периодичностью (например, раз в пять секунд). Используйте функцию sleep() для приостановки работы клиента.
3. Сервер работает не бесконечно, а прекращает работу через некоторое время (например, 30 сек). Используйте функцию clock() для определения времени работы сервера. Что будет в случае, если сервер завершит работу, не закрыв канал?

# Выполнение лабораторной работы

1. Создадим необходимые файлы с помощью команды touch. Откроем редактор emacs для их редактирования. 

![создаем файлы](image/л141.png){#fig:001 width=90%}

2. Изменим коды программ, представленнх в задании лабораторной работы. В файле common.h добавим основные заголовочные файлы. 

![изменим common.h](image/л144.png){#fig:002 width=90%}

3. В файле server.c добавим цикл while, контролирующий время работы сервера. 

![server.c](image/л143.png){#fig:003 width=90%}

4. В файле client.c добавим цикл while, отвечающий за количество сообщений о текущем времени, которое получается в результате выполнения команд.

![client.c](image/л142.png){#fig:004 width=90%}

5. Makefile - файл для сборки.

![less](image/л145.png){#fig:005 width=90%}

6. Скомпилируем необходимые файлы с помощью команды make all.

![файлы](image/л146.png){#fig:006 width=90%}

![make all](image/л147.png){#fig:007 width=90%}

7. Проверяем работу написанного кода. 

![./server](image/л148.png){#fig:008 width=90%}

# Выводы

В ходе выполнения данной лабораторной работы мы приобрели практические навыки работы с именованными каналами.

# Список литературы{.unnumbered}

::: {#refs}
:::
