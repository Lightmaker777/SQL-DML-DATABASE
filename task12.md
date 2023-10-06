# Task 12
### Show a list of musicians whose last name does not start with Y, M, C or A.
### Order the list by last name first, and then by first name. Show only rows from 5 to 10.

<pre>data=# SELECT first_name, last_name, date_of_birth, instrument FROM musician WHERE last_name NOT LIKE &apos;Y%&apos; AND last_name NOT LIKE &apos;M%&apos; AND last_name NOT LIKE  &apos;C%&apos; AND last_name NOT LIKE &apos;A%&apos; ORDER BY last_name, first_name LIMIT 5 OFFSET 4 ;
 first_name | last_name |    date_of_birth    | instrument 
------------+-----------+---------------------+------------
 Abigail    | Black     | 1969-10-11 23:08:11 | Piano
 Benjamin   | Black     | 1995-08-28 23:25:55 | Keyboard
 Evelyn     | Black     | 1951-08-20 00:36:39 | Violin
 Naomi      | Black     | 1987-03-16 00:23:44 | Harp
 Noah       | Black     | 1959-03-10 00:16:37 | Cello
(5 rows)

data=#</pre>