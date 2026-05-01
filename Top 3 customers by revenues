Select c.customer_name, 
(oi.quantity * oi.price) as revenue
from customers c
inner join orders o
on c.customer_id = o.customer_id
inner join order_items oi
on o.order_id = oi.order_id
order by revenue desc
offset 0 rows fetch next 3 rows only
