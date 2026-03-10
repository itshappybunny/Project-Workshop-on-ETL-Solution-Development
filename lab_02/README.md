# Лабораторная работа 2.1 Динамические соединения с базами данных
![ETL](https://img.shields.io/badge/-ETL-4682B4)

**Выполнила**: студентка группы АДЭУ-221
Пришлецова Кристина Сергеевна
-

**Вариант** №11. Основной фильтр по загрузке в БД: Сумма продажи: Sales > 100

Доп задание 1: Статистика по категориям

Доп задание 2: Анализ клиентов

---

**Описание логики работы Job и трансформаций**:

При помощи оркестратора Job мы запускаем скачивание данных, передаем новой переменной исходный источник данных и поочередно запускаем каждую трансформацию.

Транмация с заказами (orders) считывает данные из названной переменной выбирает определенные поля, осуществляет группировку, фильтрацию и загрузку данных в СУБД.
Аналогичным образом работают трансформации с клиентами и продуктами (customers, products).

---

**Настройки шагов  HTTP, Check File Exists оркестартора Job**:
![](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20095143.png)
![](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20095207.png)

---

**Реализация дедупликации**:
![orders](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20100001.png)
![customers](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20100038.png)
![products](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20100054.png)

---

**Результаты выполнения Job**:
![](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20100730.png)
![](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20100749.png)

--- 

**Результирующие таблицы в phpMyAdmin**:
![](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20100950.png)
![](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20101003.png)
![](https://github.com/itshappybunny/Project-Workshop-on-ETL-Solution-Development/blob/main/lab_02/images/Screenshot%202026-03-10%20101014.png)
