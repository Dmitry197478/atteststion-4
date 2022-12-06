Все скрипты работают на mysql

Создание базы данных

Cкрипт для создания базы данных

create_db.sql

База данных

bd.sql

Скрипты для заданий

Найти информацию о всех контрактах, связанных с сотрудниками департамента «Logistic». Вывести: contract_id, employee_name

task1.sql

Вывод:

name	contract_id
Egor Egorov	3
Egor Egorov	8
Egor Egorov	18
Egor Egorov	23
Alex Alexeev	20
Найти среднюю стоимость контрактов, заключенных сотрудников Ivan Ivanov. Вывести: среднее значение amount

task2.sql

Вывод

AVG(c.amount)
40000.0000
Найти самую часто встречающуюся локации среди всех заказчиков. Вывести: location, count

task3.sql

Вывод

location	v_o
Moscow	3
Найти контракты одинаковой стоимости. Вывести count, amount

task4.sql

Вывод

amount	countt
50000	2
150000	2
60000	2
30000	2
Найти заказчика с наименьшей средней стоимостью контрактов. Вывести customer_name, среднее значение amount

task5.sql

Вывод

customer_name	AVG(amount)
Andrew Nilov	48666.6667
Найти отдел, заключивший контрактов на наибольшую сумму. Вывести: department_name, sum

task6.sql

Вывод

name	SUM(amount)
Manufacturing	792000
