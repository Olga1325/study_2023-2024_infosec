---
## Front matter
title: "Индивидуальный проект. Этап №2"
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

Установить DVWA в гостевую систему к Kali Linux.

# Выполнение лабораторной работы

Устанавливаем DVWA через репозиторий на гитхабе(рис.[-@fig:pic1]).

![Клонирование репозитория](image/pic1.jpeg){ #fig:pic1 width=100% }

Переходим на setup DVWA и проверяем настройки(рис.[-@fig:pic2]).

![Проверка настроек](image/pic2.jpeg){ #fig:pic2 width=100% }

Создаем database в DVWA(рис.[-@fig:pic3]), (рис.[-@fig:pic4]).

![Инструкция по созданию database в DVWA](image/pic3.jpeg){ #fig:pic3 width=100% }

![Создание database в DVWA](image/pic4.jpeg){ #fig:pic4 width=100% }

Задаем логин и пароль на сайте(рис.[-@fig:pic5]).

![Создание логина и пароля](image/pic5.jpeg){ #fig:pic5 width=100% }

Устраняем неполадки в настройках сайта(рис.[-@fig:pic6]), (рис.[-@fig:pic7]), (рис.[-@fig:pic8]).

![Устранение неполадок](image/pic6.jpeg){ #fig:pic6 width=100% }

![Устранение неполадок](image/pic7.jpeg){ #fig:pic7 width=100% }

![Результат](image/pic8.jpeg){ #fig:pic8 width=100% }

# Выводы

Установила DVWA в гостевую систему к Kali Linux.

# Список литературы{.unnumbered}

::: {#refs}
:::
