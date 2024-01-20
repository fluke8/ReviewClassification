# Классификация отзывов
### Описание проекта
Попытка создать простую систему классификации отзыва. Цель - создать систему, которая определяет отзыв положительный или отрицательный.
#### Используемые технологии
- numpy
- pandas
- sklearn
- matplotlib

#### Выбранная модель 
В данной работе я использую модель наивного байесовского классификатора с мультиномиальным распределением. Эта модель хорошо подходит для работы с частотой встречаемости слов, что делает ее эффективной для анализа текстов.

#### Описание обучающего набора данных
- рейтинг
- текст

### Результаты:

Модель наивного байесовского классификатора с мультиномиальным распределением, примененная к обучающему набору данных, продемонстрировала впечатляющую производительность. Полученные результаты говорят о высокой точности классификации (Accuracy: 0.936), что подтверждается детальным анализом precision, recall и f1-score для каждого класса. Модель эффективно справляется с обнаружением положительных и отрицательных отзывов, предоставляя надежные исследовательские инструменты для анализа текстовых данных.

              precision    recall  f1-score   support

           0       0.74      0.82      0.78     13600
           1       0.97      0.95      0.96     86360

    accuracy                           0.94     99960
    macro avg      0.86      0.89      0.87     99960
    weighted avg   0.94      0.94      0.94     99960

![image](https://github.com/fluke8/ReviewClassification/assets/84039753/73252b5b-94a7-4165-95a3-f6fae23e5e1d)


