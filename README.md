# Patika-SQL-Odev11
--1.actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.
<br/>
--SELECT first_name FROM actor
--UNION
--SELECT first_name FROM customer;
<br/>
--2.actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.
<br/>
--SELECT first_name FROM actor
--INTERSECT
--SELECT first_name FROM customer;
<br/>
--3.actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.
<br/>
--SELECT first_name FROM actor
--EXCEPT
--SELECT first_name FROM customer;
<br/>
--4.İlk 3 sorguyu tekrar eden veriler için de yapalım.
<br/>
SELECT first_name FROM actor
UNION ALL
SELECT first_name FROM customer
<br/>
SELECT first_name FROM actor
INTERSECT ALL
SELECT first_name FROM customer;
<br/>
SELECT first_name FROM actor
EXCEPT ALL
SELECT first_name FROM customer;


