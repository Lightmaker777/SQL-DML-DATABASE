# Task 9

## A list with the 3 youngest piano players or guitar players named Araceli.

<pre>data=# SELECT first_name, last_name, date_of_birth, instrument FROM musician WHERE instrument = &apos;Piano&apos; AND first_name = &apos;Araceli&apos; ORDER BY date_of_birth DESC ;
 first_name | last_name |    date_of_birth    | instrument 
------------+-----------+---------------------+------------
 Araceli    | Hill      | 1997-07-29 23:38:31 | Piano
 Araceli    | Doe       | 1980-06-15 07:57:14 | Piano
 Araceli    | White     | 1971-11-01 15:02:13 | Piano
 Araceli    | Ali       | 1955-07-13 07:07:38 | Piano
(4 rows)

data=#</pre>