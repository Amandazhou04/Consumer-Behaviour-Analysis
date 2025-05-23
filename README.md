# Consumer Behaviour Analysis for Targeted Marketing
![cover image](https://github.com/Amandazhou04/Consumer-Behaviour-Analysis/blob/main/Cover.jpg)
Photo by Shamblen Studios on <a href="https://unsplash.com/photos/assorted-color-gift-boxes-F52I5BtDuhY?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
      
#### Project Overview  

As a data analyst supporing the sales & marketing department of a fashion retail company, the task here is to conduct an analysis on the recent customer purchase data to draw meaningful insights on the customer demographics, sales information and purchase behaviour. These insights should be useful to the team to better understand the customers' purchase behaviour and preferences. This will in turn equip the team with sufficient insights to formulate effective promotion strategies and targeted marketing promotion tactics.  

This project is done on Power BI and the dataset is taken from Kaggle. [Link to dataset](https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset/data)  

<details>
<summary><b>The Dataset</b></summary>
This dataset includes demographic information, purchase history, product preferences, and preferred shopping channels (online or offline). 
It constains 18 columns, 3900 records and includes the following attributes:

- Customer ID: A unique identifier assigned to each individual customer, facilitating tracking and analysis of their shopping behavior over time.
- Age: The age of the customer, providing demographic information for segmentation and targeted marketing strategies.
- Gender: The gender identification of the customer, a key demographic variable influencing product preferences and purchasing patterns.
- Item Purchased: The specific product or item selected by the customer during the transaction.
- Category: The broad classification or group to which the purchased item belongs (e.g., clothing, electronics, groceries).
- Purchase Amount (USD): The monetary value of the transaction, denoted in United States Dollars (USD), indicates the cost of the purchased item(s).
- Location: The geographical location where the purchase was made, offering insights into regional preferences and market trends.
- Size: The size specification (if applicable) of the purchased item, relevant for apparel, footwear, and certain consumer goods.
- Color: The color variant or choice associated with the purchased item, influencing customer preferences and product availability.
- Season: The seasonal relevance of the purchased item (e.g., spring, summer, fall, winter), impacting inventory management and marketing strategies.
- Review Rating: A numerical or qualitative assessment provided by the customer regarding their satisfaction with the purchased item.
- Subscription Status: Indicates whether the customer has opted for a subscription service, offering insights into their level of loyalty and potential for recurring revenue.
- Shipping Type: Specifies the method used to deliver the purchased item (e.g., standard shipping, express delivery), influencing delivery times and costs.
- Discount Applied: Indicates if any promotional discounts were applied to the purchase, shedding light on price sensitivity and promotion effectiveness.
- Promo Code Used: Notes whether a promotional code or coupon was utilized during the transaction, aiding in the evaluation of marketing campaign success.
- Previous Purchases: Provides information on the number or frequency of prior purchases made by the customer, contributing to customer segmentation and retention strategies.
- Payment Method: Specifies the mode of payment employed by the customer (e.g., credit card, cash), offering insights into preferred payment options.
- Frequency of Purchases: Indicates how often the customer engages in purchasing activities, a critical metric for assessing customer loyalty and lifetime value.

</details>

#### Customer Demographic Dashboard

![Cust Demographics](https://github.com/Amandazhou04/Consumer-Behaviour-Analysis/blob/ccf631eeb002c9c2ad002f6114eb530a139500a5/Cust%20demographic.png)

<details>
<summary><b>Key Insights</b></summary>

- Males make up majority of the customer base at 68%, while 32% are female.
- On the whole, male customers spend US$0.16 million while females spend US$0.08 million.
- Majority of customers are 46-60 years old (29.1%, 1,135), contributing U$233K in purchase amount.
- Only 27% of customers are subscribers. All subscribers are males.
- Clothing is the most popular product category across all age groups.


</details>

#### Sales Info Dashboard

![Sales info](https://github.com/Amandazhou04/Consumer-Behaviour-Analysis/blob/09dcd806908f8721c726397cc3cc4c664888844b/Sales%20info.png)

<details>
<summary><b>Key Insights</b></summary>  

- Total Sales revenue stands at U$233K
- Fall is the best season for the company, with US$60K worth of purchases made.
- In general, clothing is the top selling product category with $104K worth of purchases, of which, blouses are the best-selling item with US$10.4K worth sold.
- Sales of accessories are the lowest during the Spring season but starts to pick up during Summer & Fall.
- Lowest sales seasons for the respective product categories are:
  + Accessories: spring
  + Clothing: summer
  + Footwear: winter
  + Outerwear: summer
- Top selling items for male customers are pants and top sales season for male customers happen in winter.
- Spring season is the best season for footwear sales, after which it drops in the next few seasons, with the biggest drop taking place from summer to fall.
- Top selling items for male customers are pants and top sales season for male customers happen in winter.
- Spring season is the best season for footwear sales, after which it drops in the next few seasons, with the biggest drop taking place from summer to fall.
</details>

#### Purchase Behaviour Dashboard
![Purch Behav](https://github.com/Amandazhou04/Consumer-Behaviour-Analysis/blob/cad0daa9f9db94cf8dbe68b81ab04c0ff075c678/Purch%20Behav.png)

<details>
<summary><b>Key Insights</b></summary>

- Majority of customers make a purchase every <b>quarter</b>. Revenue worth US$68.8K.
- Less than half of customers use promo code during purchase.
- None of the users of promo code are female 
- Out of the 6 payment methods used by customers, <b>Paypal</b> is the most commonly used. However, this varies by gender. As seen in the data, credit card is the most commonly used method by females while cash is the most common among males.
  
</details>

<details>
<summary><b>Recommendations</b></summary>

As seen in the dashboards, there is varying behavioural insights among the different groups of customers. Based on these insights, ome of the recommendations are as follows:
- To increase number of subscribers in the customer base, suggest to run a subscriber acquisition campaign during the top season, in particular, might be worthwhile to execute a specific sub-campaign targeted at acquiring female subscribers.
- Majority of the purchase amount is contribued by customers in the 46-60 year old age group, suggest to execute a targeted campaign to encourage other age groups to spend more.
- As seen in the insights above, depending on the season, the lowest sales product category varies. Hence suggest to run "bundle deals" for complementary categories for different seasons. To bundle best selling product of a season with a product that is less popular during that season. Eg. PWP deals or extra saving sales promotion for blouse + accessories in Spring.
- The top sales season for male customers happen in winter, hence suggest to ride on this season and run a targeted promotion for males during winter season to incentivise them to purchase more.
- The data show that none of the users of the promo code are females. This is unusual, hence it will be beneficial to investigate reasons behind this behaviour and implement countermeasures. Some possible reasons could lie in the mode of communication of promo codes, where the communications were not targeted at female customers. 

</details>

Ending notes:
More insights can be drawn from the data with further slicing & dicing. With these insights, it can help the company better understand the preferences and purchasing behaviour of the customers as well as identify any gaps for untapped opportunities. 

Like what you see? Get in touch with me on [LinkedIn.](linkedin.com/in/amanda-z-62110417)
Note: 
This project is taken from Coursera Guided Project, [Scrape and analyze data analyst job requirements with Python](https://www.coursera.org/learn/scrape-job-postings-data-analyst/home/welcome)

