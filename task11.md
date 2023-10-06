# Task 11

## Show only the fourth youngest Harp player whose name starts with the letter M.

## Show the first name, last name and date of birth. But this time, print them as Name, Family Name and Date of birth.

<pre>data=# SELECT first_name AS Name, last_name AS &quot;Family name&quot;, date_of_birth AS &quot;Date of birth&quot; FROM musician WHERE instrument =&apos;Harp&apos; AND last_name LIKE &apos;M%&apos; ORDER BY date_of_birth ASC LIMIT 1 OFFSET 3 ;
 name  | Family name |    Date of birth    
-------+-------------+---------------------
 Lucas | Müller      | 1972-04-25 23:15:24
(1 row)

data=#</pre>