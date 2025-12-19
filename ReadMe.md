### Bank Customer Churn Analysis


### Problem Statement

Zinapay bank wants to gain insights into customer behavior, financial standing, and engagement patterns which would lead to better decision making. 

### Objective

- Understand the demographic and financial characteristics of the customers

- Identify trends and patterns in customer engagement

- Examine reasons for customer churn 


###  Approach

To achieve this, we are going to approach the analysis using the CRISP-DM (Cross-Industry Standard Process for Data Mining) Framework  

- Properly understand the business and data

- Prepare the data for analysis

-  Answer questions to help us achieve our objectives

- Draw conclusions

- Prepare a summary


## Data 

The data used for this analysis is drawn from two excel sheet - one containing customer information and another containing account information.

`CustomerId` : A unique identifier for each customer

`Surname`	The customer's last name

`CreditScore`	A numerical value representing the customer's credit score

`Geography`	The country where the customer resides (France, Spain or Germany)

`Gender`	The customer's gender (Male or Female)

`Age`	The customer's age

`Tenure`	The number of years the customer has been with the bank

`Balance`	The customer's account balance

`NumOfProducts`	The number of bank products the customer uses (e.g., savings account, credit card)

`HasCrCard`	Whether the customer has a credit card (1 = yes, 0 = no)

`IsActiveMember`	Whether the customer is an active member (1 = yes, 0 = no)

`EstimatedSalary`	The estimated salary of the customer

`Exited`	Whether the customer has churned (1 = yes, 0 = no)

# Observations and Insights

The following insights were drawn from analyzing the data:

-  Half of our customers come from France while the remaining half is spread between Germany and Spain

- On the average, customers in Germany maintain a higher account balance (120k dollars) compared to customers in Spain and France (62k dollars). 

- The average salary for each country indicates that majority of customers across the 3 countries earn around 100k dollars.

- More customers keep their money with the bank in France and Germany compared to Spain.

- There are more male customers (10% more) than female.

-  Most customers (75%) are youths (between the ages 30 - 60 yrs), 20% are young adults (between the ages of 18 and 30) and 5% are old (60 and above)

- 2x more customers (about 32% of total customers) have churned in Germany compared to Spain and France. Although we have more customers in France, more customers have churned from Germany

- 52% of customers have a credit card. 

   Our customers can be divided into 

- Customers who earn but maintain zero balance

- Very few customers who maintain high balance earn medium to high salary

- A large fraction of our customers maintain a balance between 50k euros to 150k euros and they earn from very low to high salary


- Most customers (33%) have a fair credit score (580 - 669). About apprx 7% have an excellent score (> 800).

-  Premium Customers (who have a tenure of over 5 yrs) constitute apprx 45% of our customers, stable customers (between 2 to 5 years) constitute apprx 41% and new customers (less than 2 years) about 14%

- Apprx 23% of new customers have churned and apprx 20% of stable/Premium customers. 1 in 5 customers who join the bank would likely churn

- Apprx 51% of customers use 1 products, apprx 46% of customers use 2 product, less than 3% use 3 products and less than 1% use 4 products.

-  Most customers stick to using 1/2 products even after staying with the bank for a long time 

- On the average, we have customers with the highest average account balance in Germany. In Spain and France, the average account balance is similar. 

- The average salary is similar for all countries.

- For the countries with the highest total balance, the order is France -> Germany -> Spain. The total balance in Spain is apprx half the balance in Germany/France. 

- For the countries with the highest total salary, the order is France -> Germany -> Spain. The total salary in France is apprx two times the salary in Germany/Spain. 

- Overall, the customers with the highest account balances are Smith (France), Martin(Germany) and Walker(Germany).

- Overall, the customers with the highest salaries are Yeh (France), Smith(France) and Lung(France).

By Geography/location,

The customers with the highest account balances 
- In Germany : Maltin, Walker and Wang
- In France : Smith, Brown and Wu
- In Spain : Ma, Robertson and Ch'iu

The customers with the highest salaries
- In Germany : Walker, Miller and Martin
- In France: Yeh, Smith and Lung
- In Spain : Ma, Scoth and Robertson

 Overall
- 86% of youth customers have churned and 7% each of young adults and old customers have churned

- 43% of premium customers, 41% of stable customers and 16% of new customers have churned

- More females (56%) have churned

- More customers without credit card (64%) have churned

- Customers with fewer products are more likely to churn. 69% of customers with 1 product exited.

-  Relative to the total no of customers in each age bracket, Apprx 28% of older customers have exited , 23% of youths and 8% of young adults

# Conclusion and Recommendations

- To improve customer acquisition especially in Germany and Spain, we would need to replicate strategies in France in these countries. 

- Customers tend to stay in the bank longer in France compared to the rest. This explains why they have more customers. We would to look at what they are doing right and apply same in Germany and Spain.

- Older customers are most affected by churn (28%) and our customer profile is 75% of young adult indicating that our banks is more suited for youths (30 - 60). We should find ways to attract young adults and the older population by offering value added services that cater to them. More effective strategies like a robust pension plan , higher interests rate on savings account, low to no fees on transfers/withdrawals etc

- The bank has 10% more males but more females have churned, indicating that female customers are not satisfied with our product offerings. Further investigation is needed here to trickle down on the actual cause.

- Owning credit cards and more products reduces the likelihood of churn. Efforts should be made to ensure customers subscribe to more products and get to use our credit card. 

- New customers are the most affected by churn (about 23%). This number is way beyond the acceptable value of 2% (hypothetical). Issues that they may be facing may revolve around proper onboarding, unavailability of customer support and poor customer service. 

- The customers with high account balances/salaries should be special attention to ensure that they are fully utilizing the bank's products to the fullest and have a dedicated customer support. 

- It has been found that very few customers tend to use more product offerings including those that have stayed longer in the bank. Efforts should be made to encourage customers to use more products.

- More customers (32%) have exited from Germany indicating that most of the issue leading to churn are coming from there. Efforts should be made to investigate why this is happening. 
