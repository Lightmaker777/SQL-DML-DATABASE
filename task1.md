#Task 1

### Write and execute the SQL statements to add 5 musicians of your choice to the table.

> **Hint**: to insert dates use the `'YYYY-MM-DD'` string format.

### Then, select all data from all the musicians and confirm the table now has your 5 musicians.

<pre>music=# SELECT * FROM musician ;
 first_name | last_name  |    date_of_birth    | instrument 
------------+------------+---------------------+------------
 Arturo     | Schumacher | 1994-09-17 17:45:58 | Trombone
 Chloe      | McDonald   | 1976-04-03 20:20:07 | Voice
 Ella       | Moore      | 1962-02-25 04:30:36 | Saxphone
 Itziar     | McDonald   | 1966-08-11 04:35:48 | Clarinet
 Aaliyah    | Brown      | 1993-08-20 18:26:23 | Clarinet
(5 rows)</pre>