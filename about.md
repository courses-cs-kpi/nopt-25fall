---
layout: page
title: Про предмет
description: Загальна інформація.
nav_order: 1
---

# Про предмет
{:.no_toc}

## Зміст
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{% assign overview = site.slides | where: "title", "Огляд" | first %}
{{ overview.content }}


Потрiбнi навички
: - **Математика**: знання та вміння використовувати обчислення, аналітичну геометрію, лінійну алгебру та теорію ймовірностей.
- **Програмування**: написання коду на Python.
- Рівень володіння англійською мовою не нижче А2.

Підручники
: 1. Nocedal, J., & Wright, S. J. (2006). [*Numerical optimization*](https://www.math.uci.edu/~qnie/Publications/NumericalOptimization.pdf).
1. Kochenderfer, M. J., & Wheeler, T. A. (2019). [*Algorithms for optimization*](https://algorithmsbook.com/optimization/files/optimization.pdf). Mit Press.
1. Кочура Ю. П., Гордієнко Ю. Г. (2024). [*Нейронні мережі*](https://github.com/dml-book/dml/releases/download/v0.1.10/0.1.10-final.pdf).


## На випадок повітряної тривоги 
{% assign specifics = site.slides | where: "title", "Повітряна тривога" | first %}
{{ specifics.content }}

## Особливостi
{% assign specifics = site.slides | where: "title", "Особливостi" | first %}
{{ specifics.content }}

## Система оцiнювання
{% assign grading = site.slides | where: "title", "Система оцiнювання" | first %}
{{ grading.content }}


## Кодекс честi
{% assign honorcode = site.slides | where: "title", "Кодекс честi" | first %}
{{ honorcode.content }}


## Як успішно завершити курс?
{% assign succeed = site.slides | where: "title", "Як успішно завершити курс?" | first %}
{{ succeed.content }}