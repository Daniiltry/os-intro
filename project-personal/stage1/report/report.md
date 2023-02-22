---
## Front matter
title: "Индивидуальный проект."
subtitle: "Этап 1."
author: "Колосов Даниил Дмитриевич"

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

Создание своего сайта. Настройка и проверка.

# Задание

Выполнитьь действия первого этапа по видео.

# Теоретическое введение


# Выполнение лабораторной работы

1.Скачиваем файл Hugo из с сайта github

![РИс13](image/РИс13.png){#fig:013 width=90%}

создаем файл bin и закидываем скаченный файл туда 
далее создаем репризиторий в github 
копируем ключ 
и скаием в наш Dan 
и ппроверяем

![Рис1](image/РИс1.png){#fig:001 width=90%}

Далее заходим и удаляем файл public

![Рис2](image/РИс2.png){#fig:002 width=90%}

Далее выполняем следующую команду. Получаем ссылку в конце и переходим на нее.

![РИс3](image/РИс3.png){#fig:003 width=90%}

и попадаем на наш будующий сайт 
создаем репризиторий и правильно называем его 
Далее проверяем

![РИс4](image/РИс4.png){#fig:004 width=90%}

Далее клонируем репризиторий
и автоматом создается каталог

![РИс5](image/РИс5.png){#fig:005 width=90%}
![РИс6](image/РИс6.png){#fig:006 width=90%}

переходит в наш каталог 
создаем ветку main
создаем пустой файл
добавляем файл в репризиторий

![РИс7](image/РИс7.png){#fig:007 width=90%}

переносим в ветку main
и проверяем

![РИс8](image/РИс8.png){#fig:008 width=90%}

Добавим в ветку main 
и создаем publik
Далее убираем из игнора слово publik
и проверяем

![РИс9](image/РИс9.png){#fig:009 width=90%}

Добавляем файлы 
и сайт

![РИс10](image/РИс10.png){#fig:010 width=90%}

![РИс14](image/РИс14.png){#fig:014 width=90%}

![РИс11](image/РИс11.png){#fig:011 width=90%}


![РИс12](image/РИс12.png){#fig:012 width=90%}


# Выводы

Я создал самостоятельно свой сайт 

# Список литературы{.unnumbered}

::: {#refs}
:::
