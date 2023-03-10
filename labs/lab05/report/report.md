---
## Front matter
title: "Лабораторная работа No 5"
subtitle: "Анализ файловой системы Linux.
Команды для работы с файлами и каталогами"
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

Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы.

# Выполнение лабораторной работы

1. Выполняем все примеры, приведённые в первой части описания лабораторной работы.

Копирование файлов и каталогов.

Копирование каталогов в текущем каталоге.

![Название рисунка](image/Рис1.png){#fig:001 width=90%}

Переименование файлов в текущем каталоге.

![Название рисунка](image/Рис2.png){#fig:002 width=90%}

![Название рисунка](image/Рис3.png){#fig:003 width=90%}

Изменение прав доступа.

![Название рисунка](image/Рис4.png){#fig:004 width=90%}

2. Скопируем файл /usr/include/sys/io.h в домашний каталог и назовем его
equipment. Если файла io.h нет, то используем любой другой файл в каталоге
/usr/include/sys/ вместо него.
В домашнем каталоге создаем директорию ~/ski.plases.
Переместим файл equipment в каталог ~/ski.plases.
Переименуем файл ~/ski.plases/equipment в ~/ski.plases/equiplist.
Создадим в домашнем каталоге файл abc1 и скопируем его в каталог
~/ski.plases, назовем его equiplist2.
Создадим каталог с именем equipment в каталоге ~/ski.plases.
Переместим файлы ~/ski.plases/equiplist и equiplist2 в каталог
~/ski.plases/equipment.
Создаем и переместим каталог ~/newdir в каталог ~/ski.plases и назовем
его plans.

![Название рисунка](image/Рис5.png){#fig:005 width=90%}

![Название рисунка](image/Рис6.png){#fig:006 width=90%}

![Название рисунка](image/Рис7.png){#fig:007 width=90%}

3. Определим опции команды chmod, необходимые для того, чтобы присвоить перечис-
ленным ниже файлам выделенные права доступа, считая, что в начале таких прав
нет

![Название рисунка](image/Рис8.png){#fig:008 width=90%}

![Название рисунка](image/Рис9.png){#fig:009 width=90%}

4. Проделаем приведённые ниже упражнения, записывая в отчёт по лабораторной
работе используемые при этом команды:

![Название рисунка](image/Рис10.png){#fig:010 width=90%}

5. Прочитаем man по командам mount, fsck, mkfs, kill и кратко их охарактеризуйте,
приведя примеры.

![Название рисунка](image/Рис11.png){#fig:011 width=90%}


# Выводы

Мы молодцы.

# Список литературы{.unnumbered}

::: {#refs}
:::
