# Telecom customer churn prediction

### Customer Churn:
Customer churn refers to the rate at which customers stop doing business with a company or cease their subscription to a service. It's a critical metric for businesses, especially those with subscription-based models, as retaining existing customers is often more cost-effective than acquiring new ones.

  ![image](https://github.com/Lavanya-pomeo/EDA-on-customer-churn/assets/167072478/fd55a1d1-054c-4e5b-b77f-df43e0546453)

### Customer Churn in Telecom Industry
In the telecom industry, customer churn refers to the rate at which subscribers terminate their contracts or switch to another service provider. It's a crucial metric for telecom companies because acquiring new customers can be expensive, and retaining existing ones is often more cost-effective.


### Dataset

https://github.com/Lavanya-pomeo/EDA-on-customer-churn/blob/main/customer_churn_dataset-testing-master.csv
https://github.com/Lavanya-pomeo/EDA-on-customer-churn/blob/main/customer_churn_dataset-training-master.csv


### Data Description

**CustomerID**: Unique identifier for each customer

**Age**: Age of the customer

**Gender**: Gender of the customer

**Tenure**: Duration as a customer in the company (in months)

**Usage Frequency**: Frequency of service usage

**Support Calls:** Number of support calls made by the customer 

**Payment Delay**: Delay in payment by the customer

**Subscription Type**: Type of subscription chosen by the customer (Standard,Basic,Premium)

**Contract Length**: Length of the subscription contract (Monthly,Quaterly,Annual)

**Total Spend**: Total amount spent by the customer 

**Last Interaction**: Customer's last interaction with the company (in days)

**Churn**: Indicator of whether the customer has churned (1 for churned, 0 for retained)


### Findings from EDA


**1.** The analysis indicates that a number of variables, including age, tenure, support calls, and last interaction, influence the causes for customer attrition

**2.** More young customers left the service

**3.** Customers who called for assistance more frequently left the company

**4.** Less expensive customers tended to defect more frequently

**5.** 22.400597052845526 % is the percentage of customers who left after spending more than the average overall

**6.** The proportion of departed clients whose overall spending was below average was 34.31012267711963 %

**7.** Customers with shorter tenure (less than 20 months) and lower total spend (less than 200) have the highest churn rate; as tenure and total spend rise, the churn rate falls

**8.** The lowest customer churn rate is seen among those with the longest tenure (over 60 months) and highest total spend (above 1000).

**9.** 17.3% customers churned out with less tenure and more payment delay

**10.** 47% of churned out customers had made more support calls(>5) which means they churned out because of unresolved issues

**11.** customers who opted for premium monthly contact(35%) got churned


### Possible Solutions


**--> Customers tend to have more unresolved issues. So solving these issues may tend to increase customer retention**

**1.** Improve customer care services through proper training to employees

**2.** Try to solve issues quickly

**3.** checking weather issue resolved or not

**4.** Getting feedback from customers and acting on it

**5.** Maintaining or improving services to avoid issues


**--> Issues related to money**

**1.** Consider lowering the premium cost as 35% of customers who opted premium services got churned out

**2.** Keeping a track on less spending customers and resolving their issues through ineraction or feedback

**3.** Giving some time for paying as customers with delayed payment tend to churn more

**4.** Providing EMI services to ease the payment method


**--> Attract new customers**

**1.** Advertising about the services clearly with attractful packages may attract new customers

**2.** Giving special services to students may reduce attrition of young customers and may also attracts new customers











