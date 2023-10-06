# Task 6

## Bernhard Schwarzenegger: Piano

<pre>data=# UPDATE musician SET instrument = &apos;Piano&apos; WHERE first_name = &apos;Bernhard&apos; AND last_name = &apos;Schwarzenegger&apos; ;
UPDATE 1</pre>

<pre>data=# SELECT instrument FROM musician WHERE first_name = &apos;Bernhard&apos; AND last_name = &apos;Schwarzenegger&apos; ;
 instrument 
------------
 Piano
(1 row)

</pre>