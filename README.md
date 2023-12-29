# Predictive-Analytics-in-Economics
Using consumer data and search analytics to understand markets and improve forecasts

## Описание:

В данном проекте я исследую то, как такие экономические показатели как индекс потребительских настроений и индекс поиска влияет на курс доллара и оборот розничной торговли. После предварительного анализа рядов двух последних переменных и таких преобразований как приведение к стационарности рядов и преобразование Бокса-Кокса для стабилизации дисперсии я использую модель ARIMA для обучения на данных и прогнозирования валютного курса и оборота розничной торговли как без экзогенных переменных, так и с. Точность моделей проверяю с помощью метрики MAE. Также строю Leave one out прогнозы.

## Результаты:

Основным результатом проделанной работы является улучшение точности прогноза USD по сравнению с обычной ARIMA моделью при использовании обоих индексов, что говорит о том, что индексы поиска и Левады содержут информацию о том, что в данный момент происходит в экономике, и их текущее значение помогает предсказать это.

## Мысли для дальнейшей работы:

Вообще говоря, данные у нас месячные. Если бы частота данных была бы повыше, эффект от добавления индексов в модели мог бы быть сильнее. Это хорошая почва для размышления для отдельного исследования

## Использованные технологии:

python, pandas, numpy, seaborn, matplotlib, pmdarima, sktime

## Ссылка на проект:

[View Predictive Analytics in Economics Notebook](./Time_Series_1.ipynb)
