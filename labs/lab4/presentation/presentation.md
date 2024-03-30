---
## Front matter
lang: ru-RU
title: Дискреционное разграничение прав в Linux. Расширенные атрибуты
author: |
	 Боровиков Даниил Александрович\inst{1}

institute: |
	\inst{1}Российский Университет Дружбы Народов

date: 26 сентября, 2022, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

---

# Цели и задачи работы

## Цель лабораторной работы

Получение практических навыков работы в консоли с расширенными атрибутами файлов.

# Процесс выполнения лабораторной работы

## Теоретическое введение 

Помимо прав доступа каждый из файлов стандартной файловой системы Linux имеет набор атрибутов, регламентирующих особенности работы с ним. Chattr - это команда в Linux, 
которая позволяет пользователю устанавливать и снимать определенные атрибуты файла. Доступны следующие атрибуты: a, A, c, C, D, e, i, j, s, S, t, u.

## Права доступа

![Права доступа](image/01.png){ #fig:001  width=70%}

## Расширенный атрибут а

![атрибут -a](image/02.png){ #fig:002  width=70%}

## Атрибут -а снят

![аАтрибут -а снят](image/03.png){ #fig:003  width=70%}

## Расширенный атрибут i

![атрибут -i](image/04.png){ #fig:004  width=70%}

## Вывод

Получены практические навыки работы в консоли с расширенными атрибутами файлов. 
