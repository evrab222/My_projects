# Анализ текстов

[ipynb](https://github.com/evrab222/My_projects/blob/master/Проект%20для%20интернет%20магазина%20'Викишоп'/P11_Portfolio.ipynb)

## Описание проекта

Требуется анализировать комментарии пользователей на английском языке и выделять токсичные, чтобы отправить на модерацию.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- nltk.stem.**WordNetLemmatizer**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.neighbors.**KNeighborsClassifier** 
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**RandomizedSearchCV**
- **matplotlib**



## Вывод

Была проведена исследовательская работа по обработке текстов и обучению и выбору модели для определения токсичных комментариев метрикой F1. Выбрана LogisticRegression. Намечены шаги по дальнейшей настройке модели.