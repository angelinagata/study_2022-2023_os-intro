---
## Front matter
title: "Отчет по лабораторной работе №7"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.


# Выполнение лабораторной работы

Изучили информацию о mc, вызвав в командной строке man mc (рис. @fig:001).

![Информация о mc](image/1.jpg){#fig:001 width=70%}

Запустили из командной строки mc (рис. @fig:002).

![Запустили mc](image/2.jpg){#fig:002 width=70%}

Выполняем несколько операций в mc, используя управляющие клавиши. Например, операция перемещения файла (рис. @fig:003).

![Перемещение файла](image/3.jpg){#fig:003 width=70%}

Выполняем основные команды меню левой (правой) панели (рис. @fig:004).

![Команды левой (правой) панели](image/4.jpg){#fig:004 width=70%}

Используя возможности подменю "Файл", выполняем: например, просмотр содержимого текстового файла (рис. @fig:005).

![Просмотр содержимого файла](image/5.jpg){#fig:005 width=70%}

Далее изучаем подменю "Команда" (рис. @fig:006).

![Подменю "Команда"](image/6.jpg){#fig:006 width=70%}

Вызовим подменю "Настройки", изучим внешний вид командной оболочки (рис. @fig:007).

![Подменю "Настройки"](image/7.jpg){#fig:007 width=70%}

Далее создаем текстовый файл (рис. @fig:008).

![Создание текстового файла](image/8.jpg){#fig:008 width=70%}

Вставляем в него текст из Интернета (рис. @fig:009).

![Редактирование файл](image/9.jpg){#fig:009 width=70%}

Проделываем с текстом манипуляции: удаляем строку текста, выделяем фрагмент текста, выделяем фрагмент текста и переносим его на новую строку, сохраняем файл. (рис. @fig:0010).

![Манипуляции с текстом](image/10.jpg){#fig:0010 width=70%}



# Выводы

В ходе выполнения лабораторной работы мы освоили основные возможности командной оболочки Midnight Commander.

# Список литературы{.unnumbered}

::: {#refs}
:::
