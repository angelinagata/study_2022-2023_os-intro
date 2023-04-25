---
## Front matter
title: "Отчет по лабораторной работе №12"
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

Изучить основы программирования в оболочке ОС UNIX. Научиться писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

# Выполнение лабораторной работы

Первая программа (рис. @fig:001).

![Первая программа](image/1.jpg){#fig:001 width=70%}

Выполнение первой программы (рис. @fig:002).

![Выполнение первой программы](image/2.jpg){#fig:002 width=70%}

Вторая программа (рис. @fig:003).

![Вторая программа](image/3.jpg){#fig:003 width=70%}

Выполнение второй программы (рис. @fig:004).

![Выполнение второй программы](image/4.jpg){#fig:004 width=70%}

Третья программа (рис. @fig:005).

![Третья программа](image/5.jpg){#fig:005 width=70%}

Выполнение третьей программы (рис. @fig:006).

![Выполнение третьей программы](image/6.jpg){#fig:006 width=70%}

# Выводы

В ходе выполнения данной лабораторной работы мы научились писать более сложные командные файлы.

# Список литературы{.unnumbered}

::: {#refs}
:::
