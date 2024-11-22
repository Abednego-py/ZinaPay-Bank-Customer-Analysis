### Bank Customer Churn Analysis


### Problem Statement

Zinapay bank wants to gain insights into customer behavior, financial standing, and engagement patterns which would lead to better decision making. 

### Objective

`Demographic Analysis`:
Analyze the distribution of customers based on geography, gender, and age.
Identify any demographic segments (e.g., by geography or gender) that have a significantly different credit score, balance, or other financial metrics.

`Customer Engagement Patterns`:
Investigate the relationship between customer tenure and engagement (such as the number of products owned, HasCrCard, and IsActiveMember).
Analyze the impact of tenure on customer behavior, especially focusing on long-term customer patterns (e.g., do longer-tenured customers tend to hold more products or have higher balances?).

`Financial Performance`:
Explore credit score distribution and identify which customer segments (e.g., age, gender, geography) tend to have higher or lower credit scores.
Analyze customer balance and estimated salary patterns and compare them across different demographic groups.

`Exited Customers Analysis`:
Compare the financial and demographic characteristics of customers who exited the bank versus those who remain active.
Identify possible factors (e.g., age, credit score, balance) associated with customers exiting the bank.

`Customer Segmentation`:
Based on the available data, identify distinct customer segments (e.g., high-balance vs. low-balance customers) and analyze their unique characteristics.
Provide insights into how the bank could optimize its services for each segment, such as offering tailored products to certain demographics or improving engagement with less active members.


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

# Insights

The following insights were drawn from analyzing the data:

-  Half of our customers come from France while the remaining half is spread between Germany and Spain

- There are more male customers (10% more) than female.

- Most customers (79%) are youths (between the ages 30 - 60 yrs) while the remaining (21%) are young adults (between the ages of 18 and 30)

- More customers exited from Germany (32%) of customers. In France and Spain, about 16% of customers have exited

- 52% of customers have a credit card

- Most customers (33%) have a fair credit score (580 - 669). About apprx 7% have an excellent score (> 800).

-  Premium Customers (who have a tenure of over 5 yrs) constitute apprx 45% of our customers, stable customers (between 2 to 5 years) constitute apprx 41% and new customers (less than 2 years) about 14%

- Apprx 23% of new customers have churned and apprx 20% of stable/Premium customers

- Apprx 51% of customers use 1 products, apprx 46% of customers use 2 product, less than 3% use 3 products and less than 1% use 4 products.

- The longer the customers stay in the bank, the more products they tend to use. However, very few customers tend to use 3/4 products. 

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

- 92% of youths have churned and 8% of young adults have churned

- 43% of premium customers, 41% of stable customers and 16% of new customers have churned

- More females (56%) have churned

- More customers without credit card (64%) have churned

# Conclusion and Recommendations

- Customer acquisition should be improved on in Spain/Germany while consolidating efforts in France. We can replicate customer acquisition efforts in France in Spain/Germany.

- Our customer profile is 18% of young adult indicating that our banks is more suited for youths (30 - 60). We should find ways to attract young adults (18-20)yrs using 

- We have 10% more males but more females have churned, indicating that we need to investigate why customers that are females are churning. Efforts should be made to address this churn.

- There is a good probability (64%) that customers without credit card churn. Encouraging customers to obtain credit cards can address this.

- 16% of new customers churn. There should be efforts to reduce this number to less than 2% by giving them incentives and addressing challenges they may be facing.

- The customers with high account balances/salaries should be further investigated to ensure that they are fully utilizing the bank's products to the fullest and giving special attention

- We have more premium customers in France. We should replicate efforts in Germany/Spain to attract premium customers in Germany/Spain.

- It has been found that very few customers tend to use more product offerings including those that have stayed longer in the bank. Efforts should be made to encourage customers to use more products.

- More customers (32%) have exited from Germany indicating that most of the issue leading to churn are coming from there. Efforts should be made to investigate why this is happening. 

- 