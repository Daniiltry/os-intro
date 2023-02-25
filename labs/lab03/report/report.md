---
## Front matter

title: "Лабораторная работа 3."
subtitle: "Markdown"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

– Сделайте отчёт в формате Markdown.

# Выполнение лабораторной работы

1. Добавление фото
Закидываем фото в папку image
далее указываем путь к ней
Ставим название фото
меняем Fig и указываем размер фото

![ Рис 1. ](image/111.png){#fig:001 width=90%}

2. Введение текста
Текст мы можем добавлять в любом порядке
Важно ставить табы между фото и тестом, иначе они будут сливаться

![ Рис 2. ](image/222.png){#fig:002 width=90%}

3. Разделение странц

![ Рис 3. ](image/333.png){#fig:003 width=90%}

4. После всех действий нажимаем кнопкук сохранить

![ Рис 4. ](image/444.png){#fig:004 width=90%}

5. Закрываем и в консоли с указанием путя пишем make

![ Рис 5. ](image/555.png){#fig:005 width=90%}

6. Проверяем и радуемся жизни.

![ Рис 6. ](image/666.png){#fig:006 width=90%}

# Вывод

Научились делать отчет в Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
