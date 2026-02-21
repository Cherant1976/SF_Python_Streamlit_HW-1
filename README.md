# <center> Учебный проект программы Data Science платформы [Skillfactory](http://skillfactory.ru). </center>

## Оглавление  
[1. Описание учебного проекта](https://github.com/Cherant1976/SF_Head_Hunter_Project_2#Описание-учебного-проекта)   
[2. Краткая информация о данных](https://github.com/Cherant1976/SF_Head_Hunter_Project_2#Краткая-информация-о-данных)  
[3. Инофрмация о вводе данных:](https://github.com/Cherant1976/SF_Head_Hunter_Project_2#Этапы-выполнения-заданий-учебного-проекта)  
[4. Используемые библиотеки python](https://github.com/Cherant1976/SF_Head_Hunter_Project_2#Используемые-библиотеки-python)    

### Описание учебного проекта    
Учебный проект на платформе [**SkillFactory**](https://skillfactory.ru/).: В проекте реализовано построенте Кредитного калькулятора с расчётом платежей и детальным графиком погашения.

:arrow_up:[к оглавлению](https://github.com/Cherant1976/SF_Head_Hunter_Project_2#Оглавление)


### Используемые формулы для расчётов Кредитного калькулятора:
Для расчётов Кредитного калькулятора используются формулы *Аннуитетного* и *Дифференцированного* платежа.  
Формулы для расчёта указанных платежей можно посмотреть по [**ссылке**](https://www.raiffeisen.ru/wiki/kak-rasschitat-procenty-po-kreditu/)

:arrow_up:[к оглавлению](https://github.com/Cherant1976/SF_Head_Hunter_Project_2#Оглавление)


### Информация о вводе данных:
Пользователь вводит данные Кредита:
+ **Сумма кредита**
+ **Процентная ставка кредита**
+ **Срок кредита**
+ **Дата выдачи кредита**

В **настройках ввода данных** пользователь может настроить вид, в котором ему удобней вводить данные кредита
  
:arrow_up:[к оглавлению](https://github.com/Cherant1976/SF_Head_Hunter_Project_2#Оглавление)

### Информация о выводе данных:
На соновании данных, указанных в полях ввода, в отдельных вкладках для *Аннуитетного* и *Дифференцированного* платежа формируются основная информация о выплатах по Кредиту и ниже формируются таблицы с графиками этих выплат.


### Используемые библиотеки *python*:  
**streamlit** *ые*, **pandas** *pd*, **datetime import datetime, date, timedelta**, **math import ceil**
```python
import streamlit as st
import pandas as pd
from datetime import datetime, date, timedelta
from math import ceil
```

:arrow_up:[к оглавлению](https://github.com/Cherant1976/SF_Head_Hunter_Project_2#Оглавление)