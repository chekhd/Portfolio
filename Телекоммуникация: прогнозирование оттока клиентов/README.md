# Телекоммуникация
## Задача
Требуется построить модель машинного обучения для прогнозирования оттока клиентов оператора связи с целью сокращения издержек

## Используемые библиотеки  
- **pandas**  
- **numpy** 
- **seaborn**  
- **matplotlib**  
- sklearn.model_selection.**train_test_split**  
- sklearn.preprocessing.**StandardScaler**  
- sklearn.preprocessing.**OneHotEncoder**  
- sklearn.linear_model.**LogisticRegression**  
- sklearn.ensemble.**RandomForestClassifier**  
- sklearn.metrics.**roc_auc_score**  
- sklearn.metrics.**roc_curve**  
- sklearn.metrics.**confusion_matrix**  
- sklearn.metrics.**accuracy_score**  
- sklearn.metrics.**precision_score**  
- sklearn.metrics.**precision_score**  
- sklearn.metrics.**recall_score**  
- sklearn.metrics.**f1_score**  
- sklearn.model_selection.**cross_val_score**  
- sklearn.model_selection.**RandomizedSearchCV**  
- catboost.**CatBoostClassifier**  
- catboost.**Pool**  
- catboost.**cv**  
- **pandasql**  
- **time**  
- **phik**  
- phik.report.**plot_correlation_matrix**

## Общие выводы
Обучено три вида моделей, а именно логистической регрессии, случайного леса и CatBoostClassifier. Лучший результат показала CatBoostClassifier, и именно эта модель использовалась на тестовой выборке.  
Также данные модели протестированы на эффективность снижения издержек компании.


