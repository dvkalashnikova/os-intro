---
## Front matter
lang: ru-RU
title: Индивидуальный проект
subtitle: Часть 2
author:
  - Калашникова Д. В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 19 марта 2025
## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
 
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Калашникова Дарья Викторовна
  * Студент
  * Российский университет дружбы народов
  * [1132243108@pfur.ru](mailto:1132243108@pfur.ru)

:::
::: {.column width="30%"}

:::
::::::::::::::

## Цель работы

Создать индивидуальный сайт, постепенно его заполняя

## Задание

Разместить фотографию владельца сайта.  
Разместить краткое описание владельца сайта (Biography).  
Добавить информацию об интересах (Interests).  
Добавить информацию от образовании (Education).  
Сделать пост по прошедшей неделе.  
Добавить пост на тему по выбору

## Обновление фотографии

Для начала нужно обновить фотографию, добавив её в папку blog/content/authors/admin

![Обновление фотографии](image/1.jpg){#fig:001}

## заполнение базовой информации о себе

Теперь добавим информацию о себе в файле _index.md

![заполнение базовой информации о себе](image/2.jpg){height=60%}

## Интересы и образование

Добавим там же информацию об интересах и об образовании 

![Интересы и образование](image/3.jpg){height=60%}

## Пост о прошедшей неделе

Напишем пост о прошедшей неделе в папке posts

![Пост о прошедшей неделе](image/4.jpg){height=60%}

## Пост о CI/CD

И о CI/CD 

![Пост о CI/CD](image/5.jpg){height=60%}

## Обновление репозитория

Теперь зальём изменения на github

![Обновление репозитория](image/6.jpg){height=60%}

## Обновление репозитория

И обновим репозиторий с github pages

![Обновление второго репозитория](image/7.jpg){height=60%}

## Выводы

В результате работы были добавлены основные элементы об авторе, а также написано 2 поста
