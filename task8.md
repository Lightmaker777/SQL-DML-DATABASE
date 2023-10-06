# Task 8

## List of first names, last names and instruments of all piano and guitar players sorted by instrument and, if the instrument is the same, then sorted by last name.

<pre>data=# SELECT first_name, last_name, instrument FROM musician WHERE instrument IN (&apos;Piano&apos;, &apos;Guitar&apos;) ORDER BY instrument, last_name;</pre>

<pre>first_name |   last_name    | instrument 
------------+----------------+------------
 Julia      | Adams          | Guitar
 Ahmed      | Anniston       | Guitar
 Abdul      | Clark          | Guitar
 Marc       | Green          | Guitar
 Araceli    | Hutticher      | Guitar
 Benjamin   | Johnson        | Guitar
 Arnold     | Lewis          | Guitar
 Araceli    | Lewis          | Guitar
 Anna       | Masferrer      | Guitar
 David      | McDonald       | Guitar
 Nikolas    | McDonald       | Guitar
 Julia      | Miller         | Guitar
 Loretta    | Muller         | Guitar
 Grace      | Nguyen         | Guitar
 Lucas      | Sanchez        | Guitar
 Nikolas    | White          | Guitar
 Arturo     | Williams       | Guitar
 Liam       | Young          | Guitar
 Benjamin   | Ahmas          | Piano
 Itziar     | Ahmas          | Piano
 Araceli    | Ali            | Piano
 Loretta    | Allen          | Piano
 Abigail    | Black          | Piano
 Aarya      | Black          | Piano
 David      | Clark          | Piano
 ...
</pre>