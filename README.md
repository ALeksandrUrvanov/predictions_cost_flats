# Построение модели прогнозирования оттока клиентов


## Задача:

В проекте вам нужно обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году. На основе данных нужно предсказать медианную стоимость дома в жилом массиве. Обучите модель и сделайте предсказания на тестовой выборке. Для оценки качества модели используйте метрики RMSE, MAE и R2.


## Используемые библиотеки
- pandas
- python
- spark


## Итоги проекта

Метрики оценки модели без категориальных переменных: 
RMSE: 81097.491594
MAE: 58068.517936
r2: 0.511866

Метрики оценки модели с категориальными переменными: 
RMSE: 73713.406219
MAE: 52746.654759
r2: 0.596710

По результату исследования модель с категориальными переменными показала лучшие показатели, хотя модель далека от идеальной. При выборе из двух модели, выберем модель с категориальными переменными.

```python

```
