# Восстановление золота из руды
## Задача
Построить модель машинного обучения для предсказания коэффициента восстановления золота из золотосодержащей руды. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.
## Используемые библиотеки  
- **pandas**  
- **seaborn**  
- **matplotlib**  
- sklearn.preprocessing.**StandardScaler**  
- sklearn.model_selection.**cross_val_score**  
- sklearn.model_selection.**RandomizedSearchCV**  
- sklearn.linear_model.**LinearRegression**  
- sklearn.tree.**DecisionTreeRegressor**  
- sklearn.ensemble.**RandomForestRegressor**  
- sklearn.metrics.**make_scorer**  
- sklearn.dummy.**DummyRegressor**
## Выводы
В работе созданы и обучены различные модели для грубой и финальной очистки. Лучшие результаты показали модели случайного леса, поэтому они использовались на тестовой выборке. Итоговый sMAPE составил 7.05.



