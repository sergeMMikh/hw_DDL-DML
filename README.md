# Домашнее задание к занятию «Работа с данными (DDL/DML)» - Михалёв Сергей

### Задание 1
1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

1.2. Создайте учётную запись sys_temp. 

1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

1.4. Дайте все права для пользователя sys_temp. 

1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

1.6. Переподключитесь к базе данных от имени sys_temp.

Для смены типа аутентификации с sha2 используйте запрос: 
```sql
ALTER USER 'sys_test'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
```
1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.

1.7. Восстановите дамп в базу данных.

1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

*Результатом работы должны быть скриншоты обозначенных заданий, а также простыня со всеми запросами.*

**Результат**

1.1 Установка MySQL произведена в соответсвии с [инструкцией на digitalocean](https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-22-04), результат приведён на скришоте ниже:

<img src="images/Task_1_1.png" alt="Task_1_1.png" width="500" height="auto">

1.2 Создал учётную запись sys_tempo:

<img src="images/Task_1_2.png" alt="Task_1_2.png" width="500" height="auto">
