# 11 Aggregates and joins:

#11.4
**select c.customer_name, c.suburb, o.order_date, o.order_total
from customers c
join orders o on c.customer_id = o.customer_id;**

| customer_name | suburb       | order_date | order_total |
| ------------- | ------------ | ---------- | ----------- |
| Alice         | Broadmeadows | 2026-01-10 | 250.00      |
| Alice         | Broadmeadows | 2026-02-15 | 420.00      |
| Alice         | Broadmeadows | 2026-02-22 | 180.00      |
| Ben           | Craigieburn  | 2026-01-05 | 120.00      |
| Ben           | Craigieburn  | 2026-02-22 | 300.00      |
| Chloe         | Glenroy      | 2026-01-18 | 550.00      |
| Chloe         | Glenroy      | 2026-02-10 | 650.00      |
| Chloe         | Glenroy      | 2026-03-12 | 700.00      |
| Daniel        | Broadmeadows | 2026-02-01 | 90.00       |
| Daniel        | Broadmeadows | 2026-03-05 | 150.00      |
| Daniel        | Broadmeadows | 2026-03-18 | 220.00      |
| Ella          | Sunbury      | 2026-01-25 | 800.00      |
| Ella          | Sunbury      | 2026-02-20 | 720.00      |

___

# 11.5 
1. **select count(o.order_id), c.customer_name
from orders o 
join customers c on c.customer_id = o.customer_id
GROUP BY c.customer_name**

| count | customer_name |
| ----- | ------------- |
| 3     | Chloe         |
| 2     | Ben           |
| 3     | Alice         |
| 2     | Ella          |
| 3     | Daniel        |
---

2. **select count(customer_id), suburb
from customers
group by suburb**

| count | suburb       |
| ----- | ------------ |
| 1     | Craigieburn  |
| 2     | Broadmeadows |
| 1     | Sunbury      |
| 1     | Glenroy      |
***

3. **select count(o.order_id), c.suburb
from orders o
join customers c on c.customer_id = o.customer_id
group by c.suburb**

| count | suburb       |
| ----- | ------------ |
| 2     | Craigieburn  |
| 6     | Broadmeadows |
| 2     | Sunbury      |
| 3     | Glenroy      |
___

# 11.6
1. **select min(o.order_total), c.customer_name
from orders o 
join customers c on c.customer_id = o.customer_id
group by c.customer_name
order by min(o.order_total) desc**

| min    | customer_name |
| ------ | ------------- |
| 720.00 | Ella          |
| 550.00 | Chloe         |
| 180.00 | Alice         |
| 120.00 | Ben           |
| 90.00  | Daniel        |
***

2. **select min(orders.order_total), customers.suburb
from customers
join orders on orders.customer_id = customers.customer_id
group by customers.suburb 
order by min(orders.order_total) desc;**

| min    | suburb       |
| ------ | ------------ |
| 720.00 | Sunbury      |
| 550.00 | Glenroy      |
| 120.00 | Craigieburn  |
| 90.00  | Broadmeadows |
---

3. **select duck.customer_name, min(mars.order_total)
from customers duck
join orders mars on duck.customer_id = mars.customer_id
group by duck.customer_name
order by min(mars.order_total)
limit 1;**

| customer_name | min   |
| ------------- | ----- |
| Daniel        | 90.00 |
___

# 11.7 Acitivty 3 MAX() with join 

1. **select max(jbhifi.order_total), australian.customer_name
from orders jbhifi
join customers australian on australian.customer_id = jbhifi.customer_id
group by australian.customer_name
order by max(jbhifi.order_total) desc**

| max    | customer_name |
| ------ | ------------- |
| 800.00 | Ella          |
| 700.00 | Chloe         |
| 420.00 | Alice         |
| 300.00 | Ben           |
| 220.00 | Daniel        |
***

2. **select car.customer_name, max(olive.order_total)
from customers car
join orders olive on car.customer_id = olive.customer_id
group by car.customer_name
having car.customer_name = 'Ben';**

| customer_name | max    |
| ------------- | ------ |
| Ben           | 300.00 |
---