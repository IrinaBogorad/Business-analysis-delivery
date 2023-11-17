# Business-analysis-delivery
Amazon Redshift SQL
Task 1
We have 
-orders.csv
-customers.csv
-stores.csv

![image](https://github.com/IrinaBogorad/Business-analysis-delivery/assets/121512167/f66c0b81-47f4-48d8-a066-a5aafd561d07)

We need to build a report of the previous month (last closed month), that
includes the following information at the city level::
- Total number of orders
- Average spend in euros
- Total number of orders coming from food partners
- Share of orders that were delivered in less than 45 minutes
- Share of orders coming from top food stores.
- Number of customers who made their first order (New Customers)
- Average monthly orders by recurrent users (with recurrent we mean they had also
made an order the month before (AMORU) )

Task 2
We have
- users.csv
- c_orders.csv
  ![image](https://github.com/IrinaBogorad/Business-analysis-delivery/assets/121512167/3cfbb444-0ca3-45eb-a5cb-af1d779081a0)

  Need to build one SQL query to create a cohort of Signup to First Order and
show the result. The objective of this cohort is to see, out of the users that signed up
in Week N, how many did their first order in Week N+1, N+2, N+3...

Task 3
We have c_orders.csv
![image](https://github.com/IrinaBogorad/Business-analysis-delivery/assets/121512167/203ca44b-ee54-4bb1-be56-594dfc0137f7)

Need to build a sql query to get the difference in days between an order and
the previous order that the same customer placed.

