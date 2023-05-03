---
## Front matter
lang: ru-RU
title: Лабораторная работа №14
subtitle: Именованные каналы
author:
  - Заболотная Кристина
institute:
  - Российский университет дружбы народов, Москва, Россия

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

  * Заболотная Кристина Александровна
  * Студент группы НБИбд-01-22
  * Российский университет дружбы народов

## Цели и задачи

Приобретение практических навыков работы с именованными каналами.

## Содержание исследования

1. Создадим необходимые файлы с помощью команды touch. Откроем редактор emacs для их редактирования. 

![создаем файлы](image/л141.png){#fig:001 width=90%}

##

2. Изменим коды программ, представленнх в задании лабораторной работы. В файле common.h добавим основные заголовочные файлы. 

![изменим common.h](image/л144.png){#fig:002 width=90%}

##

3. В файле server.c добавим цикл while, контролирующий время работы сервера. 

![server.c](image/л143.png){#fig:003 width=90%}

##

4. В файле client.c добавим цикл while, отвечающий за количество сообщений о текущем времени, которое получается в результате выполнения команд.

![client.c](image/л142.png){#fig:004 width=90%}

##

5. Makefile - файл для сборки.

![less](image/л145.png){#fig:005 width=90%}

##

6. Скомпилируем необходимые файлы с помощью команды make all.

![файлы](image/л146.png){#fig:006 width=90%}

##

![make all](image/л147.png){#fig:007 width=90%}

7. Проверяем работу написанного кода. 

![./server](image/л148.png){#fig:008 width=90%}

## Итоговый слайд

В ходе выполнения данной лабораторной работы мы приобрели практические навыки работы с именованными каналами.


