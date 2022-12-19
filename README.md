# SqlOdev5
1) select * from film
where title like '%n'
order by length DESC
limit 5;
2) select * from film
where title like '%n'
order by length 
limit 10
offset 5;
3) select last_name from customer
where store_id=1
order by last_name
limit 4;
