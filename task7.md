# Task 7

## Since all are named Araceli and play the piano, do not show the first name nor the instrument in the output

<pre>data=# SELECT last_name, date_of_birth FROM musician WHERE first_name = &apos;Araceli&apos; AND instrument = &apos;Piano&apos; ;
 last_name |    date_of_birth    
-----------+---------------------
 Ali       | 1955-07-13 07:07:38
 Hill      | 1997-07-29 23:38:31
 Doe       | 1980-06-15 07:57:14
 White     | 1971-11-01 15:02:13
(4 rows)

data=# </pre>
