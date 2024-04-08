# Оптимизация управления персоналом для компании "Работа с заботой"
https://github.com/5Misha/My-Skills/blob/main/Откат_сотрудников/Откат_сотрудников.ipynb 

## Задача проекта
Первая — построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика.
Вторая задача — построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании

## Используемые интсрументы
pandas, numpy, matplotlib.pyplot, seaborn  
from phik import resources, report  
Pipeline  
OneHotEncoder, OrdinalEncoder, StandardScaler, MinMaxScaler, LabelEncoder  
ColumnTransformer, SimpleImputer, RandomizedSearchCV  
Regression, KNeighbors, DecisionTree, SVC  
make_scorer, roc_auc_score  
## Используемые функции:  
* analiz - для вывода различной информации о таблице
* optimize_memory_usage - для оптимизации числовых типов данных
* numbers_plot - функция для построения гистограмм и ящиков с усами для каждого признака
* kategory_col - для зображения категориальных признаков в виде столбчатых диаграмм
* smape - для создания новой метрики
* best_model - при передаче трех датафреймов находит лучшую модель и считает метрику (пайплайн)

## 
