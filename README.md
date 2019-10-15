# Northwind
Hypothesis testing using data from a fictional supply chain company

Kyle Johnson

Please see the notebook titled "Northwind" for the full details and process.

Blog post:  https://kylejohnson363.github.io/northwind_traders_database_project

### Project Motivation
The purpose of this project is to practice using information from multiple databases to test several hypotheses regarding the fictional company Northwind Traders.  The dataset was created years ago by Microsoft in order to demonstrate the functionality of a new product they were marketing; the dataset has since been used in many courses regarding databasing and data science.  

### Process Overview
Below is a visualization of how the databases are set up and related to each other.  This was used to answer several business intellegence questions that will be described below.

![Diagram](https://github.com/kylejohnson363/Northwind/blob/master/Northwind_ERD.png)

### Question 1 - Do discounts increase quantity sold or revenue per order?
- Discounts do increase the quantity sold per order but there is not a specific level of discount that is superior to others, meaning that simply being able to advertise something as "discounted" increases the quantity sold.
- Discounts in general do not increase revenue per order but a discount of 5% increases revenue per order by an amount that is basically neglidgible in practice.

![](https://github.com/kylejohnson363/updated-images/blob/master/Discounts.png?raw=true)
The image above shows a distribution plot of the revenue of orders that have and do not have discounts.  As we can see, there is not a significant difference between the curves.
 
### Question 2 - Do discounts increase quantity sold or revenue per order on certain product groups?
- Discounts increase quantity per order in the categories Condiments, Confections, Grains/Cereal and Produce.
- Discounts do not increase revenue per order for any product category.

### Business Intellegence Findings
The main finding is that Northwind Traders should not offer discounts because they increase the quantity that they are sending to customers but do not increase teh revenue that they receive, meaning that they are lowering their profit margins.

### Further Inquiry
1- I recommend that metrics on advertising and competition be obtained and studied in order to gain more useful insight for the company.

2- Obtain more useful shipping data in order to give more meaningful analysis of shipping costs, such as distance traveled and time of delivery.
