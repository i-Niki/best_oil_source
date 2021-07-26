# Выбор лучшего региона для бурения скважин
<br />
Задача постороить модель логической регрессии, которая предскажет объем запасов нефти в скважинах в выбранных регионах

## Описание

 Допустим, вы работаете в добывающей компании . Нужно решить, где бурить новую скважину.
Шаги для выбора локации обычно такие:
-В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов;<br />
-Строят модель для предсказания объёма запасов в новых скважинах;<br />
-Выбирают скважины с самыми высокими оценками значений;<br />
-Определяют регион с максимальной суммарной прибылью отобранных скважин.<br />
Предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны.
<br />
## Задача:
Обучить модель для определения региона, где добыча принесёт наибольшую прибыль. Для рассчета средней прибыли была применена техника bootstrap.

## Результат
![image](https://user-images.githubusercontent.com/58337309/126984350-325faeb4-36a4-4fa9-a7ca-25d21f3507ef.png)

# Searching best oil source
<br />
Task to build logistic regression model that will predict amount of oil in the region

## What
As oil worker I need to decide where should I make new oil wells.<br />
The follow steps will help us <br />
- Collect data that contain wells features
- Based on them build logistic regression model that will predict oil well volume in new region
- Choose the best region with best metrics 
We have trail oil from 3 regions.
## Task
To determine best region with better revenue predictions. For summing I used bootstrap
![image](https://user-images.githubusercontent.com/58337309/126986127-c2c5f83f-a9e9-46cb-8aa2-8e2eef4d6843.png)
