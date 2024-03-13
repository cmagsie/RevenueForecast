# RevenueForecast
Predictive Question: 
Predict daily, the expected revenue from each customer for the next 7 days?

Running the queries below will create the training set, comprised of two parts:
Core set: a table with historical examples of the customers and their expected revenue from each customer.
Attribute tables: additional tables with relevant information about the customers.

Finding Relevant Customers For Our Core Set
We are trying to learn how to make a daily prediction on customers.
As a basis to learn from, our training set first needs to have a table with a row for each pair of customer and day.
First, we will create a helper table that will hold all days that are within the time boundaries of your dataset. These will be our anchors in time for finding the relevant customer.
