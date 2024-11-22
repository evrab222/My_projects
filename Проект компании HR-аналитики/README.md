# проект компании HR-аналитики


[ipynb](https://github.com/evrab222/My_projects/blob/master/Проект%20компании%20HR-аналитики/P7_Portfolio.ipynb)

## Описание проекта

Компания предоставила данные с уровенем удовлетворённости сотрудника.Удовлетворённость работой напрямую влияет на отток сотрудников.Увольнения несут в себе риски для компании, особенно если уходит важный сотрудник.
Поэтому необходимо: 
- построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика.
- построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.


## Навыки и инструменты

- **python**
- **pandas**
- **scipy**
- **matplotlib**
- **seaborn**
- sklearn.linear_model.**LogisticRegression**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree**DecisionTreeRegressor**
- sklearn.tree**DecisionTreeClassifier**
- sklearn.neighbors**KNeighborsClassifier**
- sklearn.svm**SVC**
- sklearn.pipeline.**Pipeline**
- sklearn.model_selection**GridSearchCV**
- sklearn.model_selection**RandomizedSearchCV**
- sklearn.model_selection**cross_val_score**
- from sklearn.metrics**roc_auc_score**
- imblearn.over_sampling **SMOTE**
- sklearn.preprocessing.**OneHotEncoder**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**MinMaxScaler**
- sklearn.preprocessing.**LabelEncoder**


## Вывод

Разработана модель, которая предсказывает уровень удовлетворённости сотрудника.Лучшей моделью оказалась DecisionTreeRegressor().Так же после обучения четырех моделей в пайплане, лучшей моделью предсказывающей то, что сотрудник уволится из компании является DecisionTreeClassifier().У всех моделей показатели метрики в заданных проектом границах.