---
## Front matter
title: "Лабораторная работа 1"
subtitle: "Подготовка рабочего пространства"
author: "Ланцова Яна Игоревна"

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
lot: false # List of tables
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

Приобрести практические навыки работы с системой управления версиями Git.

# Выполнение лабораторной работы

Создадим репозиторий на гитхабе, чтобы выкладывать туда свои лабораторные работы (рис. [-@fig:001]).

![создание репозиторий](image/1.png){#fig:001 width=70%}

Склонируем созданный репозиторий(рис. [-@fig:002]).

![команда git clone](image/2.png){#fig:002 width=70%}

Создадим структуру реопзитория (рис. [-@fig:003]):

![структура](image/3.png){#fig:003 width=70%}

Создадим ветку main, добавим созданные папки в commit, отправим изменения на удаленный репозиторий (рис. [-@fig:004]).

![передадим изменения на удаленный репозиторий](image/4.png){#fig:004 width=70%}

Проверим изменения на github (рис. [-@fig:005]).

![все изменения применились](image/5.png){#fig:005 width=70%}

# Выводы

В процессе выполнения данной лабораторной работы я приобрела практические навыки работы с Git.

