
## Problem Statement
Northwind Database is a free, public training tool distributed by Microsoft. It details fictional order, shipping and company information for a specialty food retailer.


We're operating as a consultant, with the goal of improving profits.


Two factors could play into that simple statement: we could cut costs, or we could increase revenue.


We'll explore two questions from each category above, and move into testing whether or not what we found is statistically significant.


## Questions
Question 1: Is there a statistically significant difference in discount between categories?


Question 2: Is there a significant difference in rates between shipping companies? What about by region?


Question 3: Is there a statistically significant difference in order value by region?


Question 4: Does discount amount have a statistically significant effect on the quantity of a product in an order? If so, at what level(s) of discount?


What does it mean to be significant? Taken from Hillary Green-Lerman: The difference we're seeing is probably not due to chance. "Probably not" here refers to a degree of confidence - typically 5% As such, we'll look for p values in each instance below less than .05

## Question 1: Is there a statistically significant difference in discount between categories?

Here's a view of the Category ID and Discount amount: ![Image](https://github.com/lambertmk/Using-Northwind-Database-to-Test-Statistical-Significance/blob/master/Question%201%20EDA.png)

results

results 2

Module 3 - Mac Lambert.ipynb: Jupyer Notebook with all code work

Google Slides: https://docs.google.com/presentation/d/1XJwZnIi396V9tF4MjGPuSusLh0eqTC3wo6mN3ipixx8/edit#slide=id.p

Blog Post: https://medium.com/@ml_85095/choosing-the-right-hypothesis-test-106f9ffe9296
