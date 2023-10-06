# Task 2

### Now, execute the file [data.sql](data.sql) to load the table with additional (fake) musicians.

### Use an SQL statement to show a list of 10 musicians.

<pre>data=# SELECT * FROM musician LIMIT 10
;
 first_name |   last_name    |    date_of_birth    | instrument 
------------+----------------+---------------------+------------
 Arturo     | Schumacher     | 1994-09-17 17:45:58 | Trombone
 Chloe      | McDonald       | 1976-04-03 20:20:07 | Voice
 Ella       | Moore          | 1962-02-25 04:30:36 | Saxphone
 Itziar     | McDonald       | 1966-08-11 04:35:48 | Clarinet
 Aaliyah    | Brown          | 1993-08-20 18:26:23 | Clarinet
 Aarya      | Brown          | 1963-03-02 21:59:04 | Clarinet
 Aaliyah    | Ahmas          | 1991-02-03 09:47:31 | Harp
 Olivia     | Vidal          | 1961-08-16 03:27:31 | Piano
 Benjamin   | Schwarzenegger | 1951-01-14 06:28:48 | Clarinet
 Emma       | Ali            | 1969-08-18 14:34:42 | Voice
(10 rows)</pre>