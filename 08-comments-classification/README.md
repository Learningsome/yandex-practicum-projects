# Определение токсичных комментариев

### Направление
Проект по машинному обучению, решается задача *классификации*.

### Описание проекта
Интернет-магазин запускает новый сервис, в котором пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Я очистил и лемматизировал текст, применил два подхода к классификации текстов (LightGBM + TF-IDF и BERT модель). BERT модель на семпле из 1000 текстов показала внушительный результат accuracy - 0.96

### Задача проекта
Построение модели для определения токсичных комментариев.

### Использованные библиотеки и техники
Машинное обучение, NLP, Python, Pandas, NumPy, Sklearn, nltk, spacy, torch, transformers, tf-idf, BERT.

### Описание данных
Набор данных находится в файле 'toxic_comments.csv' и содержит набор нелемматизированных текстов из твиттера.

### Другая информация
Код в тетрадке довольно подробно описан и пояснен markdown ячейками и вставками с комментариями.
