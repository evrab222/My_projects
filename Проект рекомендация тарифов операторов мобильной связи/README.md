# проект рекомендация тарифов операторов мобильной связи

[ipynb](https://github.com/evrab222/My_projects/blob/master/Проект%20рекомендация%20тарифов%20операторов%20мобильной%20связи/P12_Portfolio.ipynb)

## Описание проекта

Необходимо построить модель для задачи классификации, которая выберет подходящий тариф, довести значением accuracy по крайней мере до 0.75.


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

были исследованы алгоритмы Decision Tree Classifier(),Logistic Regression() и RandomForestClassifier(), наилучший показатель Accuracy у RandomForestClassifier() со значением 0.8.