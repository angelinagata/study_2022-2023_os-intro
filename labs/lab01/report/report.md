---
## Front matter
title: "Отчет по лабораторной работе №1 "
subtitle: "Установка OC Linux"
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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.


# Выполнение лабораторной работы

Так как виртуальная машина уже была установлена в прошлом семестре, в этом отчете представлено просто выполнение домашней работы. Для того чтобы найти нужную информацию, воспользуемся командой grep. Для того чтобы найти версию ядра, нам нужно ввести: (рис. @fig:001).

![Версия ядра](image/1.jpg){#fig:001 width=70%}

Для того чтобы найти частоту процессора, нам нужно ввести: (рис. @fig:002).

![Частота процессора](image/2.jpg){#fig:002 width=70%}

Для того чтобы найти модель процессора, нам нужно ввести: (рис. @fig:003).

![Модель процессора](image/3.jpg){#fig:003 width=70%}

Для того чтобы найти объем доступной оперативной памяти, нам нужно ввести: (рис. @fig:004).

![Объем доступной оперативной памяти](image/4.jpg){#fig:004 width=70%}

Для того чтобы найти тип обнаруженного гипервизора, нам нужно ввести: (рис. @fig:005).

![Тип обнаруженного гипервизора](image/5.jpg){#fig:005 width=70%}

Для того чтобы найти тип файловой системы корневого раздела, нам нужно ввести: (рис. @fig:006).

![Тип файловой системы корневого раздела](image/6.jpg){#fig:006 width=70%}

Для того чтобы найти последовательность монтирования файловых систем, нам нужно ввести: (рис. @fig:007).

![Последовательность монтирования файловых систем] (image/7.jpg){#fig:007 width=70%}


# Выводы

В ходе данной лабораторной работы мы вспомнили практические навыки установки операционной системы на виртуальную машину, настроили необходимые сервисы, нашли нужную информацию.

# Список литературы{.unnumbered}

::: {#refs}
:::
