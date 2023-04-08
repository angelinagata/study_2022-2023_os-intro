---
## Front matter
title: "Отчет по лабораторной работе №9"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.


# Выполнение лабораторной работы

Создаем файл и набираем туда текст (рис. @fig:001).

![Текст в файле](image/1.jpg){#fig:001 width=70%}

Сохраняем текст, а затем вырезаем одной командой целую строку (рис. @fig:002).

![Вырез строки](image/2.jpg){#fig:002 width=70%}

Вставляем эту строку в конец файла (рис. @fig:003).

![Строка в конце файла](image/3.jpg){#fig:003 width=70%}

Выделяем область в буфер обмена, вставляем эту область в конец файла (рис. @fig:004).

![Выделение области в буфер обмена](image/4.jpg){#fig:004 width=70%}

Выводим на экран список активных буферов (рис. @fig:005).

![Активные буферы](image/5.jpg){#fig:005 width=70%}

Поделим фрейм на 4 части (рис. @fig:006).

![Фрейм на 4 части](image/6.jpg){#fig:006 width=70%}



# Выводы

В ходе выполнения данной лабораторной работы мы получили практические навыки работы с редактором Emacs.

# Список литературы{.unnumbered}

::: {#refs}
:::
