Select product_name, 
Sum(quantity) as Total_sold
from order_items
group by product_name
order by Total_sold desc
offset 0 rows fetch next 1 rows only
