# Task 5

## An instrument named Saxphone should  be Saxophone.

<pre>data=# UPDATE musician SET instrument = &apos;Saxophone&apos; WHERE instrument =&apos;Saxphone&apos;;
UPDATE 8
data=# SELECT * FROM musician WHERE instrument = &apos;Saxophone&apos;      
;
 first_name |   last_name    |    date_of_birth    | instrument 
------------+----------------+---------------------+------------
 Ella       | Moore          | 1962-02-25 04:30:36 | Saxophone
 Bernhard   | Hunter         | 1994-03-20 07:46:53 | Saxophone
 Olivia     | Hutticher      | 1969-12-02 08:52:37 | Saxophone
 Grace      | Jones          | 1959-04-15 20:19:27 | Saxophone
 Grace      | Blanc          | 1991-08-18 13:24:56 | Saxophone
 William    | Adams          | 1980-07-03 11:25:22 | Saxophone
 Bernhard   | Schwarzenegger | 1999-03-27 01:15:21 | Saxophone
 Gianna     | Hunter         | 1950-05-18 12:27:04 | Saxophone
(8 rows)

data=#</pre>