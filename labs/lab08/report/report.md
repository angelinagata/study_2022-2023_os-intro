---
## Front matter
title: "Отчет по лабораторной работе №8"
subtitle: "Дисциплина: компьютерные и информационные науки"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.


# Выполнение лабораторной работы

Создаем каталог (рис. @fig:001).

![НСоздание каталога](image/1.png){#fig:001 width=70%}

Вызываем vi и создаем файл hello.sh (рис. @fig:002).

![Создание файла](image/2.png){#fig:002 width=70%}

Сделаем файл исполняемым (рис. @fig:003).

![Исполняемый файл](image/3.png){#fig:003 width=70%}

Устанавливаем курсор в конец слова HELL второй строки, заменяем это слово на HELLO (рис. @fig:004).

![HELL - HELLO](image/4.png){#fig:004 width=70%}

Устанавливаем курсор на четвертую строку и стираем слово LOCAL (рис. @fig:005).

![Стираем слово](image/5.png){#fig:005 width=70%}

Переходим в режим вставки и набираем текст: local (рис. @fig:006).

![Набор текста](image/6.png){#fig:006 width=70%}

Устанавливаем курсор на последней строке файла, вставляем после нее новый текст (рис. @fig:007).

![Конец файла](image/7.png){#fig:007 width=70%}

Удаляем последнюю строку (рис. @fig:008).

![Удаление строки](image/8.png){#fig:008 width=70%}

Вводим команду отмены изменений и сохраняем все изменения (рис. @fig:009).

![Отмена](image/9.png){#fig:009 width=70%}



# Выводы

В ходе выполнения данной лабораторной работы мы получили практические навыки работы с редактором vi.

# Список литературы{.unnumbered}

::: {#refs}
:::
