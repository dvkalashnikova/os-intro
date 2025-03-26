---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Часть 2"
author: "Калашникова Дарья Викторовна"

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

Создать индивидуальный сайт, постепенно его заполняя. 

# Задание

Разместить фотографию владельца сайта.  
Разместить краткое описание владельца сайта (Biography).  
Добавить информацию об интересах (Interests).  
Добавить информацию от образовании (Education).  
Сделать пост по прошедшей неделе.  
Добавить пост на тему по выбору

## Выполнение работы

Для начала нужно обновить фотографию, добавив её в папку blog/content/authors/admin (рис. [-@fig:001])

![Обновление фотографии](image/1.jpg){#fig:001}

Теперь добавим информацию о себе в файле _index.md (рис. [-@fig:002])

![заполнение базовой информации о себе](image/2.jpg){#fig:002}

Добавим там же информацию об интересах и об образовании (рис. [-@fig:003])

![Интересы и образование](image/3.jpg){#fig:003}

Напишем пост о прошедшей неделе в папке posts (рис. [-@fig:004])

![Пост о прошедшей неделе](image/4.jpg){#fig:004}

И о CI/CD (рис. [-@fig:005])

![Пост о CI/CD](image/5.jpg){#fig:005}

Теперь зальём изменения на github (рис. [-@fig:006])

![Обновление репозитория](image/6.jpg){#fig:006}

И обновим репозиторий с github pages (рис. [-@fig:007])

![Обновление второго репозитория](image/7.jpg){#fig:007}

# Выводы

В результате работы были добавлены основные элементы об авторе, а также написано 2 поста

# Список литературы{.unnumbered}

::: {#refs}
:::
