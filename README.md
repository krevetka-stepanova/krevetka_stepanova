# krevetka_stepanova
# **Data Science &amp; ML**

# В этом репозитории собраны мои проекты из курса "Специалист по Data Science" Яндекс.Практикума

## [Обучение с учителем](https://github.com/krevetka-stepanova/krevetka_stepanova/blob/main/Обучение%20с%20учителем_отток%20клиентов.ipynb)


### ***Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банков-ские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.***
|Сферы деятельности|Навыки и инструменты|Шаги и выводы|
|:-----------------------|:-------------------------|:------------------|
|Бизнес, инвестиции, банковская сфера, кредитование| Pandas Matplotlib Scikit-learn|Загрузка и изучение данных, кодировка категориального признака. Обнаружение дисбаланса классов в цеелвом признаке. Обучение моделей на несбалансированных данных. Борьба с дисбалансом. Обучение моделей на сбалансированных данных с анализом метрики AUC-ROC с построением ROC-кривой. Тестирование лучшей модели. Вывод: модель Случайный лес с гиперпараметрами количества деревьев 150 и глубиной 10, обученная на сбалансированных банных методами upsampling и class_weight, является и  наиболее эффективной для предсказания поведения клиентов.|

## [Сборный проект](https://github.com/krevetka-stepanova/krevetka_stepanova/blob/main/Золотая%20руда.ipynb)

### ***Подготовка прототипа модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В моем распоряжении данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.***
|Сферы деятельности|Навыки и инструменты|Шаги и выводы|
|:-----------------------|:-------------------------|:------------------|
|Промышленность|Python Pandas Matplotlib NumPy Scikit-learn исследовательский анализ данных|Загрузка и изучение данных. Заполнение пропусков по методу ближайших соседей и изучение разницы в датасетах. Анализ данных по концентрации всех видов руды на разных стадиях очистки и обогащения. Обучение трех моделей, из которых наилучшей оказалась модель Случайный лес. Проверка модели на тестовой выборке и проверка на адекватность с помощью DummyRegressor. Вывод: модель Случайный лес с количеством деревьев 80 и глубиной 8 подходит для предсказания коэффициента восстановления золота из золотосодержащей руды.|

## [Линейная алгебра](https://github.com/krevetka-stepanova/krevetka_stepanova/blob/main/Защита%20данных.ipynb)

### ***Нужно защитить данные клиентов страховой компании «Хоть потоп». Задача разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию.***
|Сферы деятельности|Навыки и инструменты|Шаги и выводы|
|:-----------------------|:-------------------------|:------------------|
|Банковская сфера Интернет-сервисы Инвестиции Телеком|Python NumPy Scikit-learn|Загрузка и изучение данных. Математически расчет умножения матриц. Составление алгоритма преобразования данных. Проверка алгоритма. Вывод: после применения преобразованного алгоритма данные защищены без потери качества обучения.|



## [Численные методы](https://github.com/krevetka-stepanova/krevetka_stepanova/blob/main/Не%20бит%20не%20крашен.ipynb)

### ***Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В моем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Задача построить модель для определения стоимости.***
|Сферы деятельности|Навыки и инструменты|Шаги и выводы|
|:-----------------------|:-------------------------|:------------------|
|Интернет-сервисы Интернет-сайт Бизнес|Python Pandas градиентный бустинг| Загрузка и изучение данных. Данные имели много пропусков, большинство из которых удалось заполнить по другим признакам. Изучение целевого признака, очищение от сомнительных значений. Обучение 5 моделей Случайный лес, Линейная регрессия, Класс линейной регресии, ГБ LightGBM, ГБ CatBoost. Выводы: самыми точными оказались модели градиентного бустинга CatBoost и LightGBM, но так как закзчику очень важен показатель времени предсказания для быстрой работы приложения по определению цены, то лучшая модель CatBoost, которая на тестовой выборке показала результат RMSE = 1552, а время предсказания 0,88.

## [Временные ряды](https://github.com/krevetka-stepanova/krevetka_stepanova/blob/main/Такси.ipynb)

### ***Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Задача построить модель для такого предсказания.***
|Сферы деятельности|Навыки и инструменты|Шаги и выводы|
|:-----------------------|:-------------------------|:------------------|
|Бизнес Интернет-сервисы Стартапы|Python Pandas Scikit-learn statsmodels| Загрузка и изучение данных, анализ данных. Декомпозиция данных. Проведение теста Дики-Фуллера. Обучение 5 моделей 'Линейная регрессия', 'Решающее дерево', 'Случайный лес', 'ГБ LightGBM', 'ГБ CatBoost' с разными гиперпараметрами. Наименьшее RMSE показала модель градиентного бустинга CatBoost - 43.55. Выдод: что модель CatBoost лучше других подходит для пресказания количества заказов на посделующий час.|

## [Машинное обучение для текстов](https://github.com/krevetka-stepanova/krevetka_stepanova/blob/main/Викишоп.ipynb)

### ***Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Задача обучить модель классифицировать комментарии на позитивные и негативные. В моем распоряжении набор данных с разметкой о токсичности правок.***
|Сферы деятельности|Навыки и инструменты|Шаги и выводы|
|:-----------------------|:-------------------------|:------------------|
|Бизнес Интернет-сервисы Стартапы|Python Pandas BERT nltk tf-idf| |

## [Компьютерное зрение](https://github.com/krevetka-stepanova/krevetka_stepanova/blob/main/Age%202.ipynb)

### ***Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:***

•	Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;

•	Контролировать добросовестность кассиров при продаже алкоголя.
|Сферы деятельности|Навыки и инструменты|Шаги и выводы|
|:-----------------------|:-------------------------|:------------------|
|Бизнес Оффлайн|Python Keras| Обучение нейросети происходило на сервере GPU Яндекса. Для загрузки данных был спользован метод ImageDataGenerator. Была обучена нейросеть ResNet50 с восемью слоями. Вывод: после подбора параметров нейросети удалось получить нужную метрику для качественного определения возраста людей.|

## [Выпускной проект](https://github.com/krevetka-stepanova/krevetka_stepanova/blob/main/Телеком_3_1%20(2).ipynb)

### ***Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.***
|Сферы деятельности|Навыки и инструменты|Шаги и выводы|
|:-----------------------|:-------------------------|:------------------|
|Бизнес Телеком|Python Pandas Matplotlib NumPy Scikit-learn GridSearchCV градиентный бустинг|Загрузка и изучение данных. Анализ данных, создание синтетических данных, анализ корреляции признаков. Предобработка данных: приведение к нужным типам данных, обработка категориальных признаков, выделения целевого признака. Обучение моделей трех моделей, используя кросс-валидацию и GridSearchCV. Анализ точности предсказаний лучшей из обученных модели: метрики ROC-AUC и Accuracy. Вывод: модель CatBoost оказалась самой точной, она была протестирована на тестовой выборке с построением ROC-кривой и матрицы ошибок|
