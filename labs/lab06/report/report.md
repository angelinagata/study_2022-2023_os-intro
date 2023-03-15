---
## Front matter
title: "Отчет по лабораторной работе №6"
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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

# Выполнение лабораторной работы

Сначала записываем в файл file.txt названия файлов, содержащихся в каталоге /etc (рис. @fig:001).

![Записываем названия файлов ](image/1.jpg){#fig:001 width=70%}

Дописываем в этот же файл названия файлов, содержащихся в нашем домашнем каталоге (рис. @fig:002).

![Записываем названия файлов из домашнего каталога](image/2.jpg){#fig:002 width=70%}

Выводим названия файлов с расширением .conf (рис. @fig:003).

![Файлы с расширением .conf](image/3.jpg){#fig:003 width=70%}

Записываем эти файлы в текстовый файл conf.txt (рис. @fig:004).

![Запись файлов](image/4.jpg){#fig:004 width=70%}

Определяем, какие файлы в домашнем каталоге имеют имена, начинавшиеся с символа с (рис. @fig:005).

![Файлы, начинавшиеся с символа с](image/5.jpg){#fig:005 width=70%}

Выводим на экран имена файлов, начинающиеся с символа h (рис. @fig:006).

![Файлы, начинающиеся с символа h](image/6.jpg){#fig:006 width=70%}

Запускаем в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log, удаляем файл ~/logfile (рис. @fig:007).

![Файл ~/logfile](image/7.jpg){#fig:007 width=70%}

Определяем идентификатор процесса gedit (1) (рис. @fig:008).

![Идентификатор процесса gedit (1)](image/8.jpg){#fig:008 width=70%}

Определяем идентификатор процесса gedit (2) (рис. @fig:009).

![Идентификатор процесса gedit (2)](image/9.jpg){#fig:009 width=70%}

Далее просматриваем справку команды man kill (рис. @fig:0010).

![Команда man kill](image/10.jpg){#fig:0010 width=70%}

Справка команды man df (рис. @fig:0011).

![Команда man df](image/11.jpg){#fig:0011 width=70%}

Справка команды man du (рис. @fig:0012).

![Команда man du](image/12.jpg){#fig:0012 width=70%}

Команда "df -vi" (рис. @fig:0013).

![Команда "df -vi"](image/13.jpg){#fig:0013 width=70%}

Команда "du -a" (рис. @fig:0014).

![Команда "du -a"](image/14.jpg){#fig:0014 width=70%}

Команда "find -type d" (рис. @fig:0015).

![Команда "find -type d"](image/15.jpg){#fig:0015 width=70%}

# Выводы

В ходе выполнения данной лабораторной работы мы ознакомились с инструментами поиска файлов и фильтрации текстовых данных.

# Список литературы{.unnumbered}

::: {#refs}
:::
