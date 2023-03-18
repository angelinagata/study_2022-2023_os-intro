---
## Front matter
title: "Отчет по второму этапу индивидуального проекта"
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

Научиться самостоятельно создавать сайт.

# Выполнение лабораторной работы

Сначала загружаем свою аватарку, которая будет высвечиваться на титульной странице сайта (рис. @fig:001).

![Аватарка](image/1.jpg){#fig:001 width=70%}

Записываем данные о себе: изменяем биографию, сведения об образовании, заполняем свои интересы (рис. @fig:002).

![Данные о себе](image/2.jpg){#fig:002 width=70%}

Вот так выглядит начальная страница нашего сайта (рис. @fig:003).

![Начальная страница сайта](image/3.jpg){#fig:003 width=70%}

Далее пишем пост по выбору. Я выбрала тему: "Системы контроля версий. Git" (рис. @fig:004).

![Создание поста по выбору](image/4.jpg){#fig:004 width=70%}

Загружаем пост на сайт (рис. @fig:005).

![Загрузка поста по выбору](image/5.jpg){#fig:005 width=70%}

Вот так выглядит пост по выбору на сайте (рис. @fig:006).

![Пост по выбору на сайте](image/6.jpg){#fig:006 width=70%}

Создание поста о прошедшей неделе (рис. @fig:007).

![Создание поста о прошедшей неделе](image/7.jpg){#fig:007 width=70%}

Вот тае выглядит пост о прошедшей неделе на сайте (рис. @fig:008).

![Название рисунка](image/8.jpg){#fig:008 width=70%}



# Выводы

В ходе выполнения второго этапа индивидуального проекта мы научились загружать информацию о себе, выкладывать соответствующие посты.

# Список литературы{.unnumbered}

::: {#refs}
:::
