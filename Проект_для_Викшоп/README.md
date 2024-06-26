# Проект для "Викшоп"
https://github.com/5Misha/My-Skills/blob/main/Проект_для_Викшоп/Проект_для_Викшоп.ipynb 

## Задача проекта
Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Обучите модель классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок. Нужно построить модель со значением метрики качества F1 не меньше 0.75.



## Используемые библиотеки
pandas, numpy, pymystem3, Mystem, WordNetLemmatizer, word_tokenize, re  
TfidfVectorizer, train_test_split, GridSearchCV  
LogisticRegression, DecisionTreeClassifier, SVC, KNeighborsClassifier  
nltk, stopwords, f1_score

## Общий вывод
Мы помогли интернет-магазину "Викишоп" побороться с оскорбительными комментариями в их новом сервисе, где можно оставлять отзывы и отвечать другим пользователям, из-за чего между ними может возникнуть конфликт. Для этого было решено создать модель, которая сможет различать комментарии на плохие и хорошие. Перед этим мы проделил такие шаги:
* Загрузили и подготовили данные. Заказчик предоставил нам их оченб много, поэтому мы оставили часть, чтобы модели могли достаточно быстро обучиться. После этого мы их разделили на тренировочные и тестовые данные. Последние использовали только для итоговой модели, а тренировочные данные были лемматизированы, очищены и приведены в читаемый для компьютера вид с помощью NtLK. Получилась матрица размером 40000 на 67259.
* Обучение моделей. Ключевой этап проекта, в котором мы выбирали между двумя обученными моделями. Это логистическая регрессия и дерево решений. Их метрики F1 на тренировочных выборках получились такими: 0.96 и 0.78.
Лучшей моделью оказалась логистическая регрессия, которая на тестовой выборке показала результат: 0.76
