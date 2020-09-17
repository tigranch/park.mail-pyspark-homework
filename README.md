# park.mail-pyspark-homework

## Рашн

В этом проекте представлено домашнее задание для курса **"Проектирование хранилищ больших объёмов данных"** технопарка mail.ru.
Данные взяты [отсюда](https://mlbootcamp.ru/ru/round/8/sandbox/) - там же можно найти их описание.
Суть задания: нужно рассчитать агрегаты по странам. На выходе должны быть следующие поля:
1. name_country - название страны;
2. user_cnt - количество пользователей из этой страны;
3. age_avg - средний возраст пользователей. Рассчитывался как среднее от полных лет пользователей в группе на current_dt, т.е. сначала для каждого пользователя ищем, сколько ему полных лет, а затем считаем среднее;
4. men_cnt - количество пользователей-мужчин;
5. women_cnt - количество пользователей-женщин;
6. men_share - доля мужчин;
7. women_share - доля женщин;

[code.ipynb](https://github.com/tigranch/park.mail-pyspark-homework/blob/master/code.ipynb) - файл, собственно, с кодом;
[data.csv](https://github.com/tigranch/park.mail-pyspark-homework/blob/master/data.csv) - csv-файл с результатами после выполнения задания.

## English

This project includes a homework for mail.ru course **"Design of a Big Data Warehouse"**.
The data being used in code is from [here](https://mlbootcamp.ru/ru/round/8/sandbox/). You can also find description of data there.
The task is to count aggregates by countries. Ouput should include following features:
1. name_country - country name
2. user_cnt - quantity of users from particular country;
3. age_avg - average age of users. Counted as average of users' full age derived by current_dt (i.e. finding age of every user and then counting average);
4. men_cnt - quantity of men from particular country;
5. women_cnt - quantity of women from particular country;
6. men_share - share of men from particular country;
7. women_share - share of men from particular country.

[code.ipynb](https://github.com/tigranch/park.mail-pyspark-homework/blob/master/code.ipynb) - file with code;
[data.csv](https://github.com/tigranch/park.mail-pyspark-homework/blob/master/data.csv) - csv-file with the results.
