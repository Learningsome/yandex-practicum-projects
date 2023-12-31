# Защита персональных данных клиентов

### Направление
Проект по машинному обучению.

### Описание проекта
Для защиты персональных данных клиентов страховой компании мной был разработан такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Метод состоит в умножении матрицы признаков на обратимую матрицу. Затем данные можно расшифровать умножив матрицу признаков на обратную обратимую матрицу. Целевая метрика R2 проверялась с помощью линейной регрессии на исходных и зашфрованных данных. Метрики совпадают, поэтому я заключил, что метод выполняет свою функцию.

### Задача проекта
Разработка метода анонимизации персональных данных клиентов страховой компании.

### Использованные библиотеки и техники
Машинное обучение, Python, Pandas, NumPy, Sklearn, Matplotlib, Seaborn.

### Описание данных
Набор персональных данных находится в файле insurance.csv

### Другая информация
Код в тетрадке довольно подробно описан и пояснен markdown ячейками и вставками с комментариями.
