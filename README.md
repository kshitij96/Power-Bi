# Food Delivery Analytics Dashboard
 
## Business Problem: 
#### Overview:
Analyze the performance of an offline meal delivery company to aid them in making future business decisions.

#### Solution: 
Performed analysis on past 3 years of data to identity success rate of different marketing strategies, financial performance of
the delivery centres, pareto analysis, hidden insights, demand forecast for next 5 weeks for each center, city, and meal category and
presented it as an interactive dashboard in Power Bi.

## PowerBi Dashboard:
![main](https://user-images.githubusercontent.com/29229114/179781969-b3970475-dfa7-4cd0-9403-a949593ba1ae.png)


## Datasets and Data Model:
There are three different datasets:
1) **Weekly_Demand_Data.csv (Fact Table)**: Historical demand data for a meal-center combination: 
2) **Meal_Info.csv (Dimension Table)**: Meal features such as category, sub-category, current price and discount: 
3) **fulfilment_center_info.csv (Dimension Table)**: Information for fulfilment centres like center area, city information, etc.

**Date_tab (Calculated Table):** To derive extract week numbers and years based on Weekly_Demand_Data

• Data has been modelled using **Star Schema** as shown below:
![Data_model](https://user-images.githubusercontent.com/29229114/179784940-a73833f7-146b-4da2-bbe3-558bc24092bb.png)


## Questions Identified:
Following questions are identified to help the company which are answered by the Dashboard: 
1)	What is the total number of orders delivered by the company? 
2)	What is the revenue earned by the company?
3)	What is the total discounted value?
4)	Does the business follow pareto principle? 
5)	What are the top 5 selling categories?
6)	Does the operational area of the store influences the number of orders?
7)	Are emails & product features on the homepage an effective mode of promotion? 
8)	What will be the next 5 weeks forecasted weekly quantity sold for each center, city, and meal category?


## Dashboard Features:
**1) Analysis Button:* 
 The info button on each chart contains the analysis about the questions which are identified.
 ![info_buttons](https://user-images.githubusercontent.com/29229114/179788801-e9ae4905-0f39-42b1-8244-64defa3eecb5.gif)
 
**2) Clear Filter Button:**
 The clear filter button removes all the filters thus cutting down the manual effort of removing filters one by one.
![clear_filter](https://user-images.githubusercontent.com/29229114/179789477-a17f8854-e511-4a5f-a757-d1d94cca9aad.gif)

 **3) Filters:**
 There are 4 filters added: Year, Center Id, City Code, Meal Cateogory which helps to see analysis for anytime timeperiod, center, city or meal.
 
![filters](https://user-images.githubusercontent.com/29229114/179789944-05faac3a-ef09-458d-ada8-ec5c0bcb452d.gif)

NOTE: Dataset and pbix file has not been shared here, incase you need them for your project please drop a mail at arorakshitiz96@gmail.com
