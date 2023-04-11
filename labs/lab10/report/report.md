---
## Front matter
title: "Отчет по лабораторной работе №10"
subtitle: "Дисциплина: Компьютерные науки и технологии программирования"
author: "Ангелина Павловна Ким"

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

Изучить основы программирования в оболочке OC UNIX/Linux. Научиться писать небольшие командные файлы.


# Выполнение лабораторной работы

Пишем первый скрипт, который при запуске будет делать резервную копию самого себя в другую директорию в нашем домашнем каталоге. При этом файл должен архивироваться одним из архиваторов на выбор. (рис. @fig:001).

![Первый скрипт](image/1.png){#fig:001 width=70%}

Проверка работы первого скрипта (рис. @fig:002).

![Проверка первого скрипта](image/2.png){#fig:002 width=70%}

Пишем второй скрипт, который обрабатывает любое произвольное число аргументов командной строки, в том числе превышающее десять. (рис. @fig:003).

![Второй скрипт](image/3.png){#fig:003 width=70%}

Проверка работы второго скрипта (рис. @fig:004).

![Проверка второго скрипта](image/4.png){#fig:004 width=70%}

Пишем третий скрипт, аналог команды ls. (рис. @fig:005).

![Третий скрипт](image/5.png){#fig:005 width=70%}

Проверка работы третьего скрипта (рис. @fig:006).

![Проверка третьего скрипт](image/6.png){#fig:006 width=70%}

Пишем четвертый скрипт, который получает в качестве аргумента командной строки формат файла и вычисляет количество таких файлов в указанной директории (рис. @fig:007).

![Четвертый скрипт](image/7.png){#fig:007 width=70%}

Проверка работы четвертого скрипта (рис. @fig:008).

![Првоерка четвертого скрипта](image/8.png){#fig:008 width=70%}


# Выводы

В ходе выполнения данной лабораторной работы мы научились писать небольшие командные файлы.

# Список литературы{.unnumbered}

::: {#refs}
:::
