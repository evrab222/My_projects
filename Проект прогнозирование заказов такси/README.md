# Прогноз количества заказов для сервиса такси

[ipynb](https://github.com/evrab222/My_projects/blob/master/Проект%20прогнозирование%20заказов%20такси/P10_Portfolio.ipynb)

## Описание проекта

Требуется спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**mean_squared_error**
- statsmodels.tsa.stattools. **adfuller**
- sklearn.linear_model.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- catboost.**CatBoostRegressor**
- **matplotlib**

## 

## Общий вывод

Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Проведено исследование трёх типов моделей, выбрана линейная регрессия.