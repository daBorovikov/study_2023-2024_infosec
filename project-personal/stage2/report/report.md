---
## Front matter
title: "Отчет об индивидуальном проекте №2"
subtitle: "Дисциплина: Информационная безопасность"
author: "Боровиков Даниил Александрович"

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

Установить DVWA в гостевую систему к Kali Linux и проверить его работу.

# Теоретическое введение

DVWA (или проклятый уязвимый веб-сервер) - это веб-приложение на PHP/MySQL, основная цель которого - стать помощником для профессионалов в области безопасности.

# Описание результатов выполнения задания:

Клонируем репозиторий github(рис. [-@fig:001])

![ Клонируем репозиторий](image/1.png){ #fig:001 width=70% }

Устанавливаем скрипт DVWA(рис. [-@fig:002])

![ Устанавливаем скрипт](image/2.png){ #fig:002 width=70% }

Запускаем скрипт DVWA(рис. [-@fig:003])

![ Запускаем скрипт](image/3.png){ #fig:003 width=70% }

Получаем ссылку на сайт и пароль с логином и переходим по ней(рис. [-@fig:004])

![ Получаем ссылку на сайт и пароль с логином](image/4.png){ #fig:004 width=70% }

Сайт DVWA(рис. [-@fig:005])

![ Сайт DVWA](image/5.png){ #fig:005 width=70% }

Создание базы данных(рис. [-@fig:006])

![ Создадим базу данных](image/6.png){ #fig:006 width=70% }


# Вывод

В ходе индивидуального проекта мы установили DVWA в гостевую систему к Kali Linux и проверили его работу.
