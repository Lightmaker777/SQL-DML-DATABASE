### Task 13

Show a list of musicians playing any of the following instruments:

- Guitar
- Saxophone
- Cello
- Violin
- Harp

> You are not allowed to use the `OR` operator.

<pre>data=# SELECT first_name, last_name, date_of_birth,instrument FROM musician WHERE instrument IN (&apos;Guitar&apos;, &apos;Saxophone&apos;, &apos;Cello&apos;, &apos;Violin&apos;, &apos;Harp&apos;);</pre>

<pre>first_name |   last_name    |    date_of_birth    | instrument 
------------+----------------+---------------------+------------
 Aaliyah    | Ahmas          | 1991-02-03 09:47:31 | Harp
 Noah       | Muller         | 1950-09-14 16:59:59 | Cello
 Amelia     | Martí          | 1963-10-15 14:22:20 | Violin
 Chloe      | Nguyen         | 1961-02-25 21:25:29 | Violin
 Julia      | Masferrer      | 1990-06-18 05:20:34 | Harp
 Lucas      | Young          | 1961-01-31 20:00:49 | Violin
 William    | Miller         | 1964-12-25 22:55:54 | Harp
 Naomi      | Lewis          | 1951-08-20 00:06:42 | Harp
 Evelyn     | Black          | 1951-08-20 00:36:39 | Violin
 Abdul      | Schwarzenegger | 1975-08-20 10:48:32 | Harp
 Ahmed      | Jones          | 1982-09-20 11:51:42 | Cello
 Noah       | Sanchez        | 1974-04-12 23:02:47 | Cello
 Anna       | Masferrer      | 1950-10-08 18:57:48 | Guitar
 Olivia     | Blanc          | 1964-04-13 12:45:22 | Cello
 Olivia     | Nguyen         | 2000-01-28 20:06:43 | Violin
 Julia      | Hunter         | 1986-02-12 03:15:37 | Violin
 Marc       | Fiedler        | 1993-01-03 04:21:44 | Cello
 Olivia     | Davis          | 1991-02-19 08:53:46 | Harp
 Anna       | Young          | 1960-04-09 09:38:29 | Violin
 Amelia     | Garcia         | 1992-09-25 04:34:28 | Harp
 Lucas      | Müller         | 1972-08-01 02:12:24 | Violin
 Marc       | Fiedler        | 1964-02-03 18:37:29 | Cello
 Emma       | Adams          | 1999-11-25 18:51:40 | Violin
 Ella       | Sanchez        | 1970-10-15 00:51:14 | Violin
</pre>