# проект определение стоимости автомобилей

[ipynb](https://github.com/evrab222/My_projects/blob/master/Проект%20определение%20стоимости%20автомобилей/P9_Portfolio.ipynb)

## Описание проекта

Необходимо построить модель для определения стоимости автомобиля, исходя из таких исторических данных, как технические характеристики, комплектации и цены автомобилей. Важными критериями для выбора модели являются:

- качество предсказания
- скорость предсказания
- время обучения



## Навыки и инструменты

- **python**
- **pandas**
- **scipy**
- **matplotlib**
- **seaborn**
- sklearn.linear_model.**LinearRegression**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**mean_squared_error**
- catboost**CatBoostRegressor**
- lightgbm**LGBMRegressor**
- phik.report**plot_correlation_matrix**
- sklearn.preprocessing.**OneHotEncoder**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.preprocessing.**StandardScaler** 


## Вывод

Обучил модели Linear Regression, CatBoostRegressor() c подбором лучших гиперпараметров через GridSearchCV, и LGBMRegressor()
Проверил время обучения и предсказания на всех моделях и метрику RMSE. Лучшей моделю по метрике и времени обучения оказалась LGBMRegressor()
