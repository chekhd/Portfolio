# Определение стоимости автомобилей
## Задача
Построить и протестировать модели машинного обучения для прогнозирования рыночной цены автомобиля.  
Проанализировать полученные модели и выбрать наиболее подходящую модель под критерии заказчика.

## Используемые библиотеки  
- **pandas**  
- **numpy** 
- **seaborn**  
- **matplotlib**  
- sklearn.model_selection.**train_test_split**  
- sklearn.linear_model.**LinearRegression**  
- sklearn.preprocessing.**StandardScaler**  
- sklearn.preprocessing.**OneHotEncoder**  
- sklearn.preprocessing.**OrdinalEncoder**  
- sklearn.metrics.**mean_squared_error**  
- sklearn.dummy.**DummyRegressor**  
- **LightGBM**
- statistics.**mode**
- **time**
- 
## Общие выводы
В проекте было протестировано два вида моделей: линейной регрессии и модель градиентного бустинга LightGBM.  
На тестовой выборке использована модель LightGBM с итоговым RMSE = 1799.48
