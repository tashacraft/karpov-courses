# Множественный регрессионный анализ

## Описание данных

Есть датасет с данными об автомобилях и их цены.


## Задача

Предсказать стоимость машин и понять, от каких факторов зависит ценообразование на автомобили. Узнать, какие переменные важны для прогнозирования и насколько хорошо полученная модель описывает данные.


## Используемые библиотеки
- pandas
- numpy
- statsmodels
- matplotlib
- seaborn

## Результаты

- создали новый признак Марка автомобиля (company) на основе признака Название автомобиля (CarName)
- исправили ошибки в названии марок автомобилей
- посчитали корреляцию между признаками и построили матрицу корреляции
- для построения модели линейной регрессии заменили категориальные переменные способом OHE
- построили 3 модели линейной регрессии:
	- с одним признаком horsepower
	- со всеми признаками
	- со всеми признаками, кроме марки машин
- выбрали лучшую модель на основе значений R2 и статистически незначимых коэффициентов