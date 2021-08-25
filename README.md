# kodluyoruz_sql_exam_1
question 1: SELECT title,description FROM film

question 2: SELECT * FROM film
WHERE (length>60 AND length<75)

question 3:SELECT * FROM film
WHERE (rental_rate=0.99 AND (replacement_cost=12.99 or replacement_cost=28.99))

question 4:Smith

question 5:SELECT * FROM film
WHERE (length<50 AND NOT(rental_rate=2.99 or rental_rate=4.99))
