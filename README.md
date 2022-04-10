# Лабораторная работа №4. Классификация
## М856 4 курс Курасевич Алексей Викторович

# Содержание:
* [Постановка задачи](#task)
* [Анализ данных, предобработка](#data_analysis)
* [Модель обучения и результат, оценка качества модели](#model_quality)
* [Улучшения качества модели, рекомендации](#fin)

## Постановка задачи
В задании нам предстоит исследовать данные, построить графики и схемы, позволяющие получить
информацию и визуализировать данные, обучить модель классификации,
оценить качество модели. Оформить документацию на github.com (код, данные, отчет,
презентация).

Используем датасет по ссылке:

https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset


## Анализ данных, предобработка
Данный датасет имеет следующие данные о 303 пациентах:

  - `age` - возраст пациента
  
  - `sex` - Пол пациента
  
  - `cp` - Тип боли в груди ~ 
    - `0` = типичная стенокардия, `1` = атипичная стенокардия, `2` = неангинозная боль, `3` = бессимптомная

trtbps - Артериальное давление в покое (в мм рт.ст.)

chol - Холесторал в мг/дл, полученный с помощью датчика ИМТ

fbs - (уровень сахара в крови натощак > 120 мг/дл) ~ 1 = верно, 0 = неверно

restecg — результаты электрокардиографии в покое ~ 0 = норма, 1 = норма ST-T, 2 = гипертрофия левого желудочка

thalachh - Максимальная достигнутая частота сердечных сокращений

oldpeak - Предыдущий пик

slp - Наклон

caa - Количество крупных судов

thall - результат стресс-теста с таллием ~ (0,3)

exng - Стенокардия, вызванная физической нагрузкой ~ 1 = Да, 0 = Нет

вывод - Целевая переменная


## Модель обучения и результат, оценка качества модели



## Улучшения качества модели, рекомендации

