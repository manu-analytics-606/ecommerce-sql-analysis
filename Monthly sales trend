Select Format(o.order_date, '%Y-%M') as Monthly,
	   Sum(oi.Quantity * oi.price) as Total_Revenue
from orders o
inner join order_items oi
on o.order_id = oi.order_id
group by Format(o.order_date, '%Y-%M')
