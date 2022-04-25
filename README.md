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


SOLUTION: [Check my recent blog](https://www.google.com)

#### 2. Assume you are given the table below for spending activity by product type. Write a query to calculate the cumulative spend so far by date for each product over time in chronological order. 

total_trans
|column_name| type       |
| --------- |:----------:|
|order_id   |integer     |
|user_id    |integer     |
|product_id |string      |
|spend      | float      |
|trans_date | datetime   |

SOLUTION: [Check my recent blog](https://www.google.com)

#### 3. Assume you are given the table below containing information on tweets. Write a query to obtain a histogram of tweets posted per user in 2020. 

tweets
|column_name| type       |
| --------- |:----------:|
|tweet_id   |integer     |
|user_id    |integer     |
|msg        |string      |
|tweet_date | datetime   |

SOLUTION: [Check my recent blog](https://www.google.com)
#### 4. Assume you are given the table below on user transaction. Write a query to obtain the list of customers whose first transaction was valued at $50 or more. 

user_transactions
|column_name      | type       |
| --------------- |:----------:|
|transaction_id   |integer     |
|product_id       |string      |
|user_id          |integer     |
|spend            | float      |
|transaction_date | datetime   |

SOLUTION: [Check my recent blog](https://www.google.com)

#### 5. Assume you are given the table below containing information on each user's tweets over a period of time. Calculate the 7-day rolling average of tweets by each user for every date. 

tweets
|column_name| type       |
| --------- |:----------:|
|tweet_id   |integer     |
|user_id    |integer     |
|msg        |string      |
|tweet_date | datetime   |

SOLUTION: [Check my recent blog](https://www.google.com)
