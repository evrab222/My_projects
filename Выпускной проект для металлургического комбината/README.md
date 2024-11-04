# проект: Промышленность

[ipynb](https://github.com/evrab222/My_projects/blob/master/Выпускной%20проект%20для%20металлургического%20комбината/P15_Portfolio.ipynb)

## Описание проекта

Требуеся построить модель, которая будет предсказывать последнюю температуру по всей партии, для уменьшения потребления электроэнергии на этапе обработки стали путем контроля температуры сплава.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- lightgbm.**LGBMRegressor** 
- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**
- sklearn.model_selection.**GridSearchCV**
- sklearn.preprocessing.**StandardScaler**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_absolute_error**
- phik.report.**plot_correlation_matrix**
- **matplotlib**
- **seaborn**



## Вывод

Была проведена исследовательская работа по обработке данных, обучению и выбору лучшей модели метрикой MAE. Выбрана модель CatBoostRegressor.