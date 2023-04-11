---
## Front matter
title: "Шаблон отчёта по 3 этапу индивидуального проекта"
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

Цель этого этапа проекта: добавить в сайт информацию о своих навыках, достижениях. Написать два поста: о прошедшей неделе, на выбранную тему.


# Выполнение лабораторной работы

Добавили информацию о своих навыках и умениях (рис. @fig:001).

![Навыки](image/1.png){#fig:001 width=70%}

Далее добавим информацию о своем опыте: поступление в университе (рис. @fig:002).

![Опыт](image/2.png){#fig:002 width=70%}

Добавим информацию о своих достижениях (рис. @fig:003).

![Достижения](image/3.png){#fig:003 width=70%}

Добавим пост о прошедшей неделе и пост на выбор (рис. @fig:004).

![Два поста](image/4.png){#fig:004 width=70%}

Загружаем все на гитхаб (рис. @fig:005).

![Загрузка на гитхаб](image/5.png){#fig:005 width=70%}


# Выводы

В ходе выполнения данного этапа мы добавили информацию о наших интересах, достижениях, опытах. Написали два новых поста.

# Список литературы{.unnumbered}

::: {#refs}
:::
