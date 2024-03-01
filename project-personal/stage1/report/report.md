---
## Front matter
title: "Индивидуальный проект. Этап №1"
subtitle: "Дисциплина: основы информационной безопасности"
author: "Пронякова Ольга Максимовна"

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

Научиться основным способам тестирования веб приложений

# Задание


    Найти максимальное количество уязвимостей различных типов.
    Реализовать успешную эксплуатацию каждой уязвимости.

# Выполнение лабораторной работы

Установливаю дистрибутив Kali Linux в виртуальную машину и настраиваю ее. В качестве среды виртуализации использую VirtualBox(рис.[-@fig:pic1]), (рис.[-@fig:pic2]), (рис.[-@fig:pic3]), (рис.[-@fig:pic4]).

![Установка виртуальной машины](image/pic1.jpeg){ #fig:pic1 width=100% }

![Установка виртуальной машины](image/pic2.jpeg){ #fig:pic2 width=100% }

![Установка виртуальной машины](image/pic3.jpeg){ #fig:pic3 width=100% }

![Установка виртуальной машины](image/pic4.jpeg){ #fig:pic4 width=100% }

Выбираю язык раскладки для виртуальной машины(рис.[-@fig:pic5]).

![Выбор языка](image/pic5.jpeg){ #fig:pic5 width=100% }

Ввожу логин и пароль(рис.[-@fig:pic6]), (рис.[-@fig:pic7]).

![Ввод логина](image/pic6.jpeg){ #fig:pic6 width=100% }

![Ввод пароля](image/pic7.jpeg){ #fig:pic7 width=100% }

Конечная установка машины(рис.[-@fig:pic8]), (рис.[-@fig:pic9]).

![Конечная установка машины](image/pic8.jpeg){ #fig:pic8 width=100% }

![Конечная установка машины](image/pic9.jpeg){ #fig:pic9 width=100% }

# Выводы

Успешно установила дистрибутив Kali Linux в виртуальную машину.

# Список литературы{.unnumbered}

::: {#refs}
:::
