# Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

# 1- film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
	SELECT COUNT (*) FROM film
	where length > 
	(
	SELECT AVG(length) from film
	);
# 2- film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
	SELECT COUNT (*) FROM film
	WHERE rental_rate = 
	(
	SELECT MAX(rental_rate) FROM film
	);
	
# 3- film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.
	SELECT * FROM film
	WHERE 
	rental_rate = (SELECT MIN(rental_rate) FROM film) 
	and 
	replacement_cost=(SELECT MIN(replacement_cost)FROM film);

# 4- payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
 	SELECT payment.customer_id, customer.first_name, customer.last_name, payment.payment_id, payment.amount
	FROM payment 
	INNER JOIN customer ON payment.customer_id = customer.customer_id 
	WHERE amount = (SELECT MAX(amount) FROM payment)
	ORDER BY customer_id; 
## Yada toplamda enfazla alış veriş yapanları freqeuncy özelliği kullanarak ilk 5 müşteriyi sıralayabiliriz (RFM-Recency, Frequency ve Monetary analizleri önemli)
	SELECT customer_id, count (customer_id) AS Frequency FROM payment
	GROUP BY customer_id
	ORDER BY frequency desc
	LIMIT 5;