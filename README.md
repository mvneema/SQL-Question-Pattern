# SQL-Question-Pattern
This repo is for different SQL question patterns asked in interviews.

#### 1. Write a query to list the top three cities that had the most number of completed orders. 
Assume you are given the tables below containing information on trade and users. 

Trades                                                           
| column_name   | type                            |              
| ------------- |:-------------------------------:|              
| order_id      | right-aligned                   |              
| user_id       | centered                        |              
| price         | are neat                        |              
|quantity       | integer                         |              
|status         |string ("complete", "cancelled") |
|timestamp      | datetime                        |

Users
|column_name    | type            |
| --------------|:---------------:|
|user_id        |integer          |
|city           |string           |
|email          | string          |
|signup_date    | datetime        |


SOLUTION: [Check my recent blog](https://neemaunni.wixsite.com/mysite/post/sql-questions-pattern)

#### 2. Assume you are given the table below for spending activity by product type. Write a query to calculate the cumulative spend so far by date for each product over time in chronological order. 

total_trans
|column_name| type       |
| --------- |:----------:|
|order_id   |integer     |
|user_id    |integer     |
|product_id |string      |
|spend      | float      |
|trans_date | datetime   |

SOLUTION: [Check my recent blog](https://neemaunni.wixsite.com/mysite/post/sql-questions-pattern)

#### 3. Assume you are given the table below containing information on tweets. Write a query to obtain a histogram of tweets posted per user in 2020. 

tweets
|column_name| type       |
| --------- |:----------:|
|tweet_id   |integer     |
|user_id    |integer     |
|msg        |string      |
|tweet_date |datetime    |

SOLUTION: [Check my recent blog](https://neemaunni.wixsite.com/mysite/post/sql-questions-pattern)
#### 4. Assume you are given the table below on user transaction. Write a query to obtain the list of customers whose first transaction was valued at $50 or more. 

user_transactions
|column_name      | type       |
| --------------- |:----------:|
|transaction_id   |integer     |
|product_id       |integer     |
|user_id          |integer     |
|spend            | float      |
|transaction_date | datetime   |

SOLUTION: [Check my recent blog](https://neemaunni.wixsite.com/mysite/post/sql-questions-pattern)

#### 5. Assume you are given the table below containing information on each user's tweets over a period of time. Calculate the 7-day rolling average of tweets by each user for every date. 

tweets
|column_name| type       |
| --------- |:----------:|
|tweet_id   |integer     |
|user_id    |integer     |
|msg        |string      |
|tweet_date | datetime   |

SOLUTION: [Check my recent blog](https://neemaunni.wixsite.com/mysite/post/sql-questions-pattern)

#### 6. Assume you are given the table below containing information on user sessions, including their start and end times. A session is considered to be concurrent with another user's session if they overlap. Write a query to obtain the user session that is concurrent with the largest number of other user sessions. 

sessions
|column_name| type       |
| --------- |:----------:|
|session_id |integer     |
|start_time |datetime    |
|end_time   |datetime    |

SOLUTION: [Check my recent blog](https://neemaunni.wixsite.com/mysite/post/sql-questions-pattern-part-2)

#### 7. Assum you are given a table containing measurement values obtained from a sensor over several days. Measurements are taken several times within a given day. Write a query to obtain the sum of the odd-numbered measurements and the sum of the even-numbered measuremens by date.

measurements
|column_name      | type       |
| --------------- |:----------:|
|measurement_id   |integer     |
|measurement_value|float       |
|measurement_time |datetime    |

SOLUTION: [Check my recent blog](https://neemaunni.wixsite.com/mysite/post/sql-questions-pattern-part-2)

#### 8. Assume you are given the following tables on cistomer transactions and products. Find the top 10 products that are most frequently bought together (purchased in the same transaction).

transactions
|column_name      | type       |
| --------------- |:----------:|
|transaction_id   |integer     |
|product_id       |string      |
|user_id          |integer     |
|quantity         |integer     |
|transaction_time | datetime   |

products 
|column_name      | type       |
| --------------- |:----------:|
|product_id       |integer     |
|product_name     |string      |
|price            | float      |
|transaction_date | datetime   |


SOLUTION: [Check my recent blog](https://neemaunni.wixsite.com/mysite/post/sql-questions-pattern-part-2)

#### 9. Determine the change in the number of daily violations by calculating the difference between the count of current and previous violations by inspection date. Out the inspection date and the change in the number of daily violations. Order your results by the earliest inspect first. 

sf_restaurant_health_violations
|column_name            | type       |
| --------------------- |:----------:|
|business_id            |integer     |
|business_name          |object      |
|business_address       |object      |
|business_city          |object      |
|business_state         | object     |
|business_postal_code   | float      |
|business_latitude      |float       |
|business_longitude     |float       |
|business_location      |object      |
|business_phone_number  | float      |
|inspection_id          | object     |
|inspection_date        | datetime   |
|inspection_score       | float      |
|inspection_type        | object     |
|violation_id           | object     |
|violation_description  | object     |
|risk_category          | object     |

SOLUTION: [Check my recent blog](https://neemaunni.wixsite.com/mysite/post/sql-questions-pattern-part-2)






