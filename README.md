# Insurance-Lead-Prediction
Binary classification problem

JOB-A-THON analytics Vidhya

Health Insurance Lead Prediction

•	Your Client FinMan is a financial services company that provides various financial services like loan, investment funds, insurance etc. to its customers.
•	FinMan wishes to cross-sell health insurance to the existing customers who may or may not hold insurance policies with the company.
•	The company recommends health insurance to its customers based on their profile once these customers land on the website. Customers might browse the recommended health insurance policy and consequently fill up a form to apply.
When these customers fill-up the form, their Response towards the policy is considered positive and they are classified as a lead.
•	Once these leads are acquired, the sales advisors approach them to convert and thus the company can sell proposed health insurance to these leads in a more efficient manner.
•	Now the company needs your help in building a model to predict whether the person will be interested in their proposed Health plan/policy given the information about:
	Demographics (city, age, region etc.)
	Information regarding holding policies of the customer
	Recommended Policy Information

Approach on Problem
As this is the machine learning problem, first we have to check that is it a—
•	Supervised Learning
•	Unsupervised Learning
•	Reinforcement Learning
As we have the structure data and output feature name is already predefined, we have to use Supervised Learning.
Here in supervised learning there are again two types
•	Regression   	--> To predict continuous value output
•	Classification --> To predict discrete value output
As we need output as a response from a customer is in 2 classifications
  	0 : Customer did not show interest in the recommended policy
    1 :  Customer showed interest in the recommended policy

So, obviously we will use here classification to predict 0 and 1 as discrete value output.
Again there are 2 general types in classification problems
•	Binary Classification -->  Two class labels as output.
•	Multi-class Classification --> More than two class labels as output.
So in this way, 
We are considering this problem as supervised learning with binary classification.
