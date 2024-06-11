SELECT customers.first_name, customers.last_name, company_orders.date, company_orders.order_number
FROM customers
inner join
company_orders
on 
customers.id = company_orders.customer_id
