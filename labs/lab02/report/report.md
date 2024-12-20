---
## Front matter
title: "Отчет по лабораторной работе №2"
subtitle: "Архитектура компьютера"
author: "Сафиуллина Айлина Саяровна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Изучить идеологию и применение средств контроля версий. Приобрести практические навыки по работе с системой git.

# Выполнение лабораторной работы

Я создала gmail-почту для регистрации на сайте github. Далее я начала создавать репозиторий, основываясь на шаблоне от Кулябова Дмитрия Сергеевича. (рис. [-@fig:001]).

![шаблон репозитория](image/1.png){#fig:001 width=100%}

(рис. [-@fig:002]).

![созданный репозиторий](image/2.png){#fig:002 width=100%}

Затем я настроила доступ к репозиторию из системы Linux.(рис. [-@fig:003]).

![настройка параметров](image/3.png){#fig:003 width=100%}

Для этого мне понадобилось создать SSH-ключ, который нуджен для безопасной авторизации. (рис. [-@fig:004]).

![SSH-key](image/4.png){#fig:004 width=100%}

Далее я создала локальную папку на компьютере и клонировала в нее содержимое репозитория (рис. [-@fig:005]).

![клонирование репозитория](image/5.png){#fig:005 width=100%}

(рис. [-@fig:006]).

![продолжение кода](image/6.png){#fig:006 width=100%}



# Выводы

В ходе выполнения данной лабораторной работы я освоила основные принципы работы с GitHub, создала там учетную запись, а также получила опыт работы с системой контроля версий.

