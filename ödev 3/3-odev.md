# 1. Görev
country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.

```SQL
SELECT country FROM country
WHERE country LIKE 'A%a';

```

# 2. Görev
country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.

```SQL
SELECT country FROM country
WHERE country LIKE '_____n';

```
# 3. Görev
film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.
```SQL
SELECT title FROM film
WHERE title ILIKE '%t%' AND LENGTH(title) >= 4;

```
# 4. Görev
```SQL
SELECT * FROM film
WHERE title LIKE 'T%' AND length > 90 AND rental_rate = 2.99;
```