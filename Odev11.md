Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.



1)actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.
``` 
select first_name from actor 
union 
select first_name customer
```

2)actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.
3)actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.
4)İlk 3 sorguyu tekrar eden veriler için de yapalım.
