# проект отток клиентов из банка

[ipynb](https://github.com/evrab222/My_projects/blob/master/Проект%20отток%20клиентов%20из%20банка/P13_Portfolio.ipynb)

## Описание проекта

Необходимо построить модель с предельно большим значением F1-меры, спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Дополнительно измерить AUC-ROC, сравнивайте её значение с F1-мерой.


## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- imblearn.under_sampling**RandomUnderSampler**
- imblearn.over_sampling **SMOTE**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble**RandomForestClassifier**
- sklearn.linear_model.**LogisticRegression**
- sklearn.dummy**DummyClassifier**
- sklearn.preprocessing.**OneHotEncoder**
- sklearn.preprocessing.**StandardScaler** 
- sklearn.metrics.**roc_auc_score**
- sklearn.metrics.**f1_score**
- sklearn.metrics**recall_score**



## Вывод

Были исследованы алгоритмы Decision Tree Classifier(),Logistic Regression() и RandomForestClassifier(), наилучший показатель F1 у RandomForestClassifier(). Провел взвешивание классов,а так же увеличил и уменьшил выборку и выбрал наилучшую модель для проверки на тестовой выборке. После проверки модели на тестовой выборке,метрика F1 = 0.594, что соответствует минимальному порогу задания в 0.59, AUC-ROC = 0.83.Вероятность ухода клиента из банка,меньше чем вероятность того что останется.