# Определение возраста покупателей
# Задача
Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей.  
Требуется построить модель, которая по изображению определит возраст человека.

Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы: 
- анализировать покупки покупателей определенной возрастной группы
- контролировать добросовестность кассиров при продаже алкоголя
## Используемые библиотеки  
- **pandas**  
- **seaborn**  
- **matplotlib**  
- tensorflow.keras.preprocessing.image.**ImageDataGenerator**  
- tensorflow.keras.layers.**Conv2D**  
- tensorflow.keras.layers.**AvgPool2D**  
- tensorflow.keras.layers.**Flatten**  
- tensorflow.keras.layers.**Dense**  
- tensorflow.keras.layers.**GlobalAveragePooling2D**  
- tensorflow.keras.applications.resnet.**ResNet50**  
- tensorflow.keras.models.**Sequential**  
- tensorflow.keras.optimizers.**Adam**

## Общие выводы
Обучена можель с использованием ResNet50 на предобученных весах. MAE на тестовой выборке составил 6.84.
