# Расширение фермерского хозяйства с помощью машинного обучения
https://github.com/5Misha/My-Skills/blob/main/Расширение_фермерского_хоз-ва/Расширение_фермерского_хоз-ва.ipynb

## Задача проекта
Нужно помочь владельцу молочного хозяйства «Вольный луг» купить буренок. С помощью некоторых критериев надо обучить модели для отбора коров в поголовье. Первая будет прогнозировать возможный удой у коровы, а вторая - рассчитывать вероятность получить вкусное молоко от коровы.

## Используемые библиотеки
import pandas as pd  
import numpy as np  
import matplotlib.pyplot as plt  
from scipy import stats  
import seaborn as sns  
from sklearn.model_selection import train_test_split  
from sklearn.preprocessing import OneHotEncoder, StandardScaler  
from sklearn.linear_model import LinearRegression, LogisticRegression  
from sklearn.metrics import (  
    confusion_matrix,    
    mean_absolute_error,  
    mean_squared_error,  
    r2_score,
    accuracy_score,  
    recall_score,  
    precision_score  
    )
