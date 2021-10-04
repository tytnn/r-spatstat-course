--- 
title: "Пространственная статистика и моделирование на языке R"
author: "Тимофей Самсонов"
date: "2021-10-04"
site: bookdown::bookdown_site
knit: "bookdown::render_book"
twitter-handle: timofeysamsonov
documentclass: book
bibliography: [references.bib, packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: tsamsonov/r-geo-course
description: "Курс лекций, посвященных использованию методов пространственной статистике и моделированию на языке R"
header-includes:
   - \usepackage[T2A]{fontenc}
   - \usepackage[utf8]{inputenc}
   - \usepackage[russian]{babel}
mainfont: Open Sans
toc_float:
  collapse: section
  smooth_scroll: true
always_allow_html: yes
---


# Введение {-}

Добро пожаловать на учебный курс __"Пространственная статистика и моделирование на языке R"__! Данный курс предназначен для уверенных пользователей R, которые имеют опыт работы с пространственными данными и хотели бы развить свои навыки в области пространственного анализа и моделирования.

::: {.rmdimportant}
Если вы впервые столкнулись с пространственными данными или никогда до этого не программировали на R, то рекомендуется начать с базового курса __[Визуализация и анализ географических данных на языке R](https://tsamsonov.github.io/r-geo-course/)__. 
:::

## Программное обеспечение {-}

Для успешного прохождения курса на вашем компьютере должно быть установлено следующее программное обеспечение:

* Язык [R](https://cran.r-project.org)
* Среда разработки [RStudio](https://www.rstudio.com/products/rstudio/download3/)

## Ссылка на пособие {-}

Если этот курс лекций оказался полезным для вас, и вы хотите процитировать его с списке литературы вашей работы, то ссылку можно оформить по следующей форме:

----
_Самсонов Т.Е._ **Пространственная статистика и моделирование на языке R.** М.: Географический факультет МГУ, 2021.
----