# Task 14

### Finally, clear the table `musician` of all data.

> You are not allowed to use the command `DELETE FROM`.

### Then, select all rows and columns from that table.

<pre>data=# TRUNCATE TABLE musician ;
TRUNCATE TABLE
data=# SELECT * FROM musician ;
 first_name | last_name | date_of_birth | instrument 
------------+-----------+---------------+------------
(0 rows)

data=#</pre>