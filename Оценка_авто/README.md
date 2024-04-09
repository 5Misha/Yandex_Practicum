# Оценка стоимости автомобилей
https://github.com/5Misha/My-Skills/blob/main/Оценка_авто/Оценка_автомобилей.ipynb 

## Задача проекта
На основе имеющихся данных требуется разработать модель, способную прогнозировать цену автомобиля на основе его характеристик. Это обеспечит удобство при продаже или покупке автомобилей и поспособствует привлечению новых клиентов

## Используемые инструменты
pandas, numpy, matplotlib.pyplot, seaborn, scipy, os    
DecisionTreeRegressor, LinearRegression, LGBMRegressor  
train_test_split, GridSearchCV    
StandardScaler, OneHotEncoder, OrdinalEncoder  
make_scorer, mean_squared_error, mean_squared_error  
cross_val_score, KFold, time  
DummyRegressor

## Используемые функции
analiz(df, cat_per) - Вывод различной информации о таблице  
optimize_memory_usage(df: pd.DataFrame, print_size: bool=True) - Оптимизация числовых типов данных
numbers_plot(df, param_hue) - Функция для построения гистограмм и ящиков с усами для каждого признака  
borders(df, column) - Функция для расчета границ выбросов  
kategory_col(df, columns) - Изображает категориальные признаки в виде столбчатых диаграмм
