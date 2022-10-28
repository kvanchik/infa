# sql-select
~урок 21.10.22

SELECT COUNT (*) FROM information_schema.tables
 > выводит общее количество таблиц
 
SELECT table_name FROM information_schema.tables
 > выводит названия всех таблиц
 
SELECT * FROM users
 > показывает содержание таблицы с названием "users"
 
SELECT  * FROM grades JOIN users ON grades.user_id = users.user_id
 > выводит оценку из "grades" и имя ее получателя из "users", т.к там есть общее поле "user_id"
