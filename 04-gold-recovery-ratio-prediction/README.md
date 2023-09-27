# Проект: Предсказание коэффициента восстановления золота

### Направление и задача
Проект по машинному обучению, решается задача *регрессии*.

### Использованные библиотеки и техники
Python, Pandas, NumPy, Sklearn, Matplotlib, Seaborn

### Описание проекта
Строитстся модель машинного обучения для промышленной компании, разрабатывающая решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. 

### Задача проекта
Спрогнозировать концентрацию золота при проведении процесса очистки золота.

### Описание данных
Данные находятся в трёх файлах:

    gold_recovery_train_new.csv — обучающая выборка;
    gold_recovery_test_new.csv — тестовая выборка;
    gold_recovery_full_new.csv — исходные данные.

Данные индексируются датой и временем получения информации (признак `date`). Соседние по времени параметры часто похожи.

Некоторые параметры недоступны, потому что замеряются и/или рассчитываются значительно позже. Из-за этого в тестовой выборке отсутствуют некоторые признаки, которые могут быть в обучающей. Также в тестовом наборе нет целевых признаков.

Исходный датасет содержит обучающую и тестовую выборки со всеми признаками.

В нашем распоряжении сырые данные: их просто выгрузили из хранилища. Прежде чем приступить к построению модели, проверим по инструкции их на корректность.


### Другая информация
Код в тетрадке довольно подробно описан и пояснен markdown ячейками и вставками с комментариями.