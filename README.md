# Shield-Insurance_Performance-Analysis
This is an Insurance data analysis to gain insights about revenue growth, customer growth, city-wise performance, sales modes and age group insights of a Company named Shield Insurance.

Live Dashboard link - https://app.powerbi.com/view?r=eyJrIjoiODEwZjZlYmYtMzZiOS00YzkwLWJlZDAtMzA2N2UzYTRkNDE2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

Youtube Video presentation link - https://www.youtube.com/embed/alhoLEBEJM8?si=60_ZWr0wVxHPUBqF

This is a part of Virtual Internship of Codebasics. For this purpose, I was asked to build interactive business intelligence dashboard to help stakeholders track and analyze the performance of an insurance company.

I was given datasets consisting of customer details like date of birth, age, city, policy details like policy number, base coverage amount, base premium amount, final premium amount. 

In the dataset there were 4 types of sales mode- Offline-Agent, Offline-Direct, Online-App, Online-Website.

The dataset given consists of data for 6 months from November 2022 till April 2023. The project required calculation of age-group, so I have calculated age as on the analysis date from the date of birth given 
and formed the age groups from 18 to above 65 years.

After that the data modelling is done accordingly connecting with the dimension and fact tables.

Coming to the dashboard, as per the mockup provided by the project, I have developed 3 dashboards in PowerBI using the insurance transaction data, the customer demographics and settlement information. 

**1st dashboard is General View** → It highlights overall revenue, customers, daily growth, city- and age-based splits and monthly trends.

**2nd dashboard is Sales Mode Analysis** → It Compares online vs offline channels, showing revenue and customer splits and sales mode trends over time.

**3rd dashboard is of Age Group Analysis** → It explores customer age demographics, expected settlements and policy preferences to analyze product targeting.

**1. Key Insights from the Shield Insurance General View Dashboard :-**

<img width="1513" height="816" alt="Dash_1a" src="https://github.com/user-attachments/assets/13ffa8a1-f343-4427-89b5-cd7240934294" />

This dashboard gives an overview of the total performance, breakdowns by city and age and monthly trends.

For Overall Business, Shield Insurance have generated a total revenue of 989.25 million rupees from 26841 customers.

- On a daily basis growth that is about 5.47 million in revenue and 148 new customers.
  
- Growth is looking good: Revenue is up by 18.40% from last month, and customers are up by 18.28%. Daily figures show slight stability with minimal changes.
  
-The Key takeaway: The insurance business is growing steadily. This positive trend means their strategies are working, but they should keep monitoring daily metrics to spot any early issues.

In the Performance by City chart it can be seen that Delhi NCR leads the pack with 11007 customers which is about 41% of total and 401.57 million in revenue , it is also around 41% total. 

- Mumbai comes to the second, with 6432 customers bringing in 239.51 million revenues. Followed by Hyderabad, Chennai and Indore.
  
- Interestingly, average revenue per customer is highest in Indore at about 40000 rupees, while it is fairly consistent around 36000-37000 in other cities.
  
- From these charts we can see that, major cities like Delhi NCR and Mumbai drive most of the business.
  
For the Performance by Age Group it can be seen that the 31-40 age group is the biggest segment, with 10593 customers which around 39% of total, generating 317.05 million in revenue , which is 32% of total.

- the next age group is 41-50 with 5878 customers and 223.70 million, followed by 25-30 -3241 customers, 57.75 million revenue, 51-65 with 2996 customers, 162.09 million revenue, 18-24 with 1943 customers, 26.77 million revenue, and 65+ with 2200 customers, 201.89 million revenue.
  
- The 65+ segment has the highest average revenue per customer at around 92000 rupees, compared to just 14000 for 18-24.
  
**So, the conclusion here is Mid-career adults from age bracket 31-50 bring in volume, but seniors with age 65+ are also high value as well.**

In the City and Age Group Breakdown table we can see in detail how age groups perform in each city. For example:

  - The highest age group is 31-40 comes from Delhi NCR and generates 130.55 million rupees revenue.
    
  - For Mumbai, the 31-40 group has 2481 customers and 74.72 million revenues.
    
  - Younger groups from 18-30 are more prominent in cities like Hyderabad and Chennai but contribute less revenue overall.
    
  - Therefore, the pattern varies by city e.g. Delhi has more young professionals while Mumbai and Indore have valuable older customers.
    
In case of Monthly Trends Revenue, it was 132 million in November 2022 and increases to 156 million in December 2022. 
Decreases to 141 million in January 2023, again slightly gets down to 139 million in February 2023, increases at 246 million in March 2023, then again falls to 154 million in April 2023. 

- In Customer trends is similar like before: Rises from November 2022 to December 2022. Then increases to 7081 in March 2023, going down in April 2023.
  
So, we can see big spikes in March 2023 and December 2022 with November 2022 as a slow spot. 

**Overall, in short, Shield Insurance is in a strong position with nearly a billion in revenue, driven by metro cities like Delhi NCR and middle-aged customers.**

**2. Key Insights from the Sales Mode Analysis Dashboard :-**

<img width="1470" height="819" alt="Dash_2" src="https://github.com/user-attachments/assets/5f429969-9a65-436b-84ed-c76920e1a57a" />

This dashboard shows how the sales are happening through different sales modes, like offline agents, offline direct, online app and online website breaking down by revenue and customers.

In the Customers by Sales Mode, the pie chart shows that the majority of the customers, about 55.41%,  come through offline agents. This means agents in person or over the phone are bringing in the most people.

- around 16.03% customers come from the online app, 15.86% from offline direct like walk-ins or calls without agents, and only about 12.70% customers are from the online website.
  
- In the Revenue by Sales Mode pie chart, it tells the same story. The offline agents generate the most revenue, at around 55.67% of the total.

- Therefore it can be said that Offline agents are the main powerhouse for both customers and revenue which emphasizes the value of personal interactions in insurance sales.

- In the two monthly sales mode trend vs revenue and vs customer chart we can see fluctuations over the months- November 2022, December 2022, January 2023, February 2023, March 2023, April 2023.
  
- Across the modes, the offline agent consistently makes up the largest chunk of revenue each month. Similar story for monthly trend with customers - Here also offline agents dominate the customer count most months, aligning with the overall pie chart.
  
-  **Overall, the insurance business is strong in offline channels, particularly through agents, for both customer volume and revenue. The seasonal peaks show better performance around March and December.**

**3. Key Insights from the Sales Mode Analysis Dashboard :-**

<img width="1451" height="813" alt="Dash_3" src="https://github.com/user-attachments/assets/fa72422c-7866-4ecb-a3d5-4f06b16cb064" />


This dashboard reflects how different age groups buy the policies, different sales channels, expected settlements and monthly trends. 

- In the Total Customers by Age Group bar chart - it shows that our largest customer group is 31-40 years old, with 10593 customers which is about 39% of the total 26841.
- 
- The next group is 41-50 years old with 5878 customers , which is also 22% of total customers, after that 25-30 years, 51-65 years, 65+ years, and the youngest group is <18-24 with 1943 customers.

- From here it can be understood that working adults in their 30s and 40s make up over half the customers. It can be suggested focusing to marketing on family-oriented policies like health or life insurance to retain and grow this major group.
  
- Age Group vs. Policy Preferences table - The table shows how many customers in each age group choose specific policy types. For example, the 31-40 group leads in most policies, with high numbers in POL3309HEL - 1856 customers and POL4331HEL - 1678 customers.
  
- Younger groups (<18-24 and 25-30) prefer simpler policies like POL4321HEL.
  
- Older groups (51-65 and 65+) show stronger interest in policies like POL6303HEL and POL2005HEL, possibly with more comprehensive coverage.
  
-	Total at per policy varies with POL432HEL being the most popular of overall 4434 customers.

-	Age Group vs. Expected Settlement bar chart- This bar chart shows expected settlement amounts by age. The 31-40 group has the highest amount of 6.56K followed by 41-50, 25-30, 51-65, 65+ and lastly <18-24.  It can be siad that Middle aged group customers drive higher expected settlements, possibly due to higher coverage needs. This shows the need for risk management in these segments like preventive health programs to reduce future claims.

-	Age Group vs. Sales Mode by Customers and by Revenue charts -  here it can be seen that again Offline agents are the main reason for volume and revenue growth in all ages, but it can also be seen that few customers tend to use online channels also.
  
-	Therefore, to boost digital sales, the app and website can be further enhanced for tech-savvy persons.

-	In the Monthly Trend of Customers by Age Group chart - March is again the busiest month, led by middle aged customers. In November we can again see sales get down across different age groups.

**Conclusion :-**

1. Shield Insurance is doing well with approx. 990 million rupees in total revenue from approx. 27000 customers.
   
2. Major cities like Delhi NCR and Mumbai are our powerhouses of business generation with consistent performance across age groups. Smaller cities like Indore shows untapped potential in less urban areas where people might buy premium policies.
   
3. The 31-40 age group dominates with 39% of customers and drives peaks in sales and expected settlements.
   
4.	For Shield Insurance Sales, customers and revenue increases in March and December but dips sharply in April and November. This trend holds across sales modes, cities, and ages with middle aged groups leading the ups and downs.
   
5.	Offline agents are used by for all ages. Also expected settlements are highest for 31-40 age bracket which indicates more coverage needs in that group.

   
**In the end what can be recommended for Improvement of Performance to Shield Insurance?**

Here are some simple and straightforward ideas based on the insights:

1.	Shield insurance can strengthen the Online Channels, encourage younger age groups to shift online with discounts, which could increase efficiency and reduce offline costs.
   
2.	They can train Offline Agents for upselling, as Offline Agents bring in lots of customers, so they can provide training on selling high-value policies or add-ons, specially to middle aged groups who have higher settlement needs.
   
3.	With higher expected settlements in the 31-40 group, they can offer preventive programmes like health check-ups to reduce future claims.
   
4.	They should address the seasonal dips by running special promotions or incentives in slow moving months like November and April.
   
5.	Lastly simple metrics can be set up to monitor the changes like monthly revenue per channel or customer growth by age. Small pilot projects can be tested such as app updates or city campaigns and the data to be reviewed.

This is the end of the analysis. Thank you for reading.

Dataset obtained from Codebasics Virtual Internship 1.

