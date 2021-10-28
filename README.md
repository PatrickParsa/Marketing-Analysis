# Marketing Analysis Project

In this project, we analyze customer data to draw insights on the effectiveness of several different marketing campaigns as well as extracting patterns between different customer profiles and preferences. The dataset was obtained from Kaggle and contained the information described in the data dictionary below

## Data Dictionary

- ID : Unique ID of each customer
- Year_Birth : Age of the customer
- Education : Customer's level of education
- Marital_Status : Customer's marital status
- Kidhome : Number of small children in customer's household
- Teenhome : Number of teenagers in customer's household
- Income : Customer's yearly household income
- Recency : Number of days since the last purchase
- MntFishProducts : The amount spent on fish products in the last 2 years
- MntMeatProducts : The amount spent on meat products in the last 2 years
- MntFruits : The amount spent on fruits products in the last 2 years
- MntSweetProducts : Amount spent on sweet products in the last 2 years
- MntWines : The amount spent on wine products in the last 2 years
- MntGoldProds : The amount spent on gold products in the last 2 years
- NumDealsPurchases : Number of purchases made with discount
- NumCatalogPurchases : Number of purchases made using catalog (buying goods to be shipped through the mail)
- NumStorePurchases : Number of purchases made directly in stores
- NumWebPurchases : Number of purchases made through the company's website
- NumWebVisitsMonth : Number of visits to company's website in the last month
- AcceptedCmp1 : 1 if customer accepted the offer in the first campaign, 0 otherwise 
- AcceptedCmp2 : 1 if customer accepted the offer in the second campaign, 0 otherwise
- AcceptedCmp3 : 1 if customer accepted the offer in the third campaign, 0 otherwise
- AcceptedCmp4 : 1 if customer accepted the offer in the fourth campaign, 0 otherwise
- AcceptedCmp5 : 1 if customer accepted the offer in the fifth campaign, 0 otherwise
- Complain : 1 If the customer complained in the last 2 years, 0 otherwise
- Country: Country customer belongs to

# General Overview

## Data exploration and preprocessing

* After initial exploration of the data, we cleaned the data to make it functional for analysis and we observed the distributions and summary statistics for both the numerical and categorical values. We also created new features to aid in deeper analysis. Finally, we dealt with missing values and outliers. 

## Analysis

* Our analysis began with a concentration on the marketing campaigns and their effectiveness on the customer base. We then delved deeper by incorporating differences in income to extract information about the effect income has on whether or not a customer will accept a campaign. For example in the following graph, we can see that there is a significant different in the effectiveness of campaign 5 when you consider income. 

<img src="https://user-images.githubusercontent.com/88220704/139193739-e28fbb41-8729-49a2-b15d-359e899d2c9a.png" width="500" height="350" />

We also incorporated categorical variables to assess its effect on the efffectiveness of the marketing campaigns. For example, in the following graph we can see the differences as a result of education level. 

<img src="https://user-images.githubusercontent.com/88220704/139194126-1d35c415-36ff-4000-bc9c-f1e3497a998b.png" width="500" height="350" />




We then observed the performances across different purchasing channels to see if we can gain furtehr insights on customer spending. For instance, we split the customer base into different income bins to see if we can spot distinctions between purchasing channels. 



<img src="https://user-images.githubusercontent.com/88220704/139194702-dd44b95e-e70c-4ae8-a807-7f7638aa5083.png" width="500" height="350" />


Finally, We created a new customer profile based on characteristics we've found to be most important, so that we can therefore see the difference in acceptance of the marketing campaigns. 


<img src="https://user-images.githubusercontent.com/88220704/139195015-c399d692-b029-4e80-8b62-b545b9acf81b.png" width="500" height="350" />


## Conclusion

These insights shed light on the differences between various marketing campaigns as well as their effectiveness on certain customer profiles and ineffectiveness on others. For example, marketing campaign #2 seems largely ineffective regardless of different customer profiles, so a replication of the methods of this campaign wouldn't be advised. Likewise, the high effectiveness of marketing campaign 5 with customers with no children but weak performance with those with children might indicate a need to orchestrate a campaign that likewise specifically appeals to those dealing with parenthood. Overall, this analysis leaves us with a strong general sense of the preferences of the different profiles of the customer base, and thus future marketing campaigns can be approporiately designed depending on the present objective. 

