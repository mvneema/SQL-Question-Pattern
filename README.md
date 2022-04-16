# SQL-Question-Pattern
This repo is for different SQL question patterns asked in interviews.

#### 1. Write a query to list the top three cities that had the most number of completed orders. 
Assume you are given the tables below containing information on trade and users. 
Trades                                                           Users
| column_name   | type                            |              |column_name    | type            |
| ------------- |:-------------------------------:|              | --------------|:---------------:|
| order_id      | right-aligned                   |              |user_id        |integer          |
| user_id       | centered                        |              |city           |string           |
| price         | are neat                        |              |email          | string          |
|quantity       | integer                         |              |signup_date    | datetime        |
|status         |string ("complete", "cancelled") |
|timestamp      | datetime                        |

SOLUTION: 

#### 2. Assume you are given the table below for spending activity by product type. Write a query to calculate the cumulative spend so far by date for each product over time in chronological order. 

total_trans
|column_name| type       |
| --------- |:----------:|
|order_id   |integer     |
|user_id    |integer     |
|product_id |string      |
|spend      | float      |
|trans_date | datetime   |
