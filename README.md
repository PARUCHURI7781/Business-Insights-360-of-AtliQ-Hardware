# Business-Insights-360-of-AtliQ-Hardware 

# Introduction

* **Atliq Hardware** is a company dealing with manufacturing of computers and its peripherals having operations in various countries.
* **Problem Statement** Their business is growing rapidly and they still rely on excel files for data analytics. Excel files are hard to consume and not effective in generating insights. Also due to the lack of effective analytics the company faced a major loss in Latin America. Senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work.

# Purpose of BI dashboard :

*  To closely monitor and assess their sales operations and overall performance.
*  Analysing various parameters and trends and keeping a close eye on essential key performance indicators (KPIs).
*  Building various views for various departments like the Finance View, Sales View, Marketing View, Supply Chain View to have a more detailed analysis of the incoming data.

# Key Business Metrics that are focused upon : 

* **Revenue** : Total amount of money generated from its primary operations, typically from sales of goods or services, before deducting any expenses or costs.
* **Pre Invoice Amount**: Total amount a company charges for its products or services before issuing an invoice. These deductions can include discounts, rebates, or allowances, affecting the final invoice amount.
* **Net Invoice Sales** : Sales after subtracting pre invoice sales, reflecting the actual income received.
* **Post Invoice Deductions** : Further discounts and fees like promotional discounts, placement fees, performance rebate etc.
* **Net Sales(NS)** : Sales after subtracting post invoice deductions from Net invoice sales. This is basically the Revenue for Atliq Hardware.
* **Cost of Goods Sold (COGS)** : Cost incurred by Atliq in producing their products which includes manufacturing cost, transportation cost and other cost.
* **Gross Margin/ Gross Profit(GM)** : Profit that Atliq is making, that is, Net Sales-COGS.
* **Other expenses** : like ads and promotions. Also other operational expenses like accounting fees, rent, utilities etc.
* **Net Margin/Net Profit(NP)** : Net Profit that Atliq made, that is, GM-other expenses.
* **Net Error** : Represents the difference between a forecasted or estimated value and the actual observed/sales value. It can be positive or negative, indicating whether the prediction is overestimating or underestimating the actual value. Net error provides information about the direction and magnitude of the error.
* **Net Error%** : Net Error divided by Forecast.
* **Absolute Error** : Net error might balance it out because it is defined for certain period of time. So to get the true picture of error, absolute values are taken.
* **Forecast Accuracy** : 100- Absolute error%.

# Understanding the data : 

 ## * Customer dimension table : 

   * 74 customers with total of 209 stores spread across 27 markets/countries.
   * 2 platforms - Brick and Mortar, and E-Commmerce
   * 3 Channels - Retailer, Direct, and Distributors.

 ## * Market dimension table :

    * 27 markets spread across 7 sub-zones in 4 broad regions, that are : APAC(Asia Pacific), EU(European Union), NA(North America), LATAM(Latin America)

 ##   * Product dimension table :

    *  3 divisions : Networking and Storage (N & S), Peripherals and Accessories (P & A), PC.
    *  6 segments & 14 Categories of products.

##   * Fact tables :

    * Fact sales monthly : sales values for products. 
    * Fact forecast monthly : forecast values for products.

# Data Modelling and Relationships :
Data modeling is the process of structuring and organizing data to create relationships, and establish a framework for effective data analysis and reporting. It ensures data accuracy, facilitates complex calculations, and enhances data integration, providing a solid foundation for informed decision-making and business intelligence.

# Technical & Soft Skills: 

*  Proficiency in ETL methodology (Extract, Transform, Load).
*  Skills to generate a date table using Power Query.
*  Ability to derive fiscal months and quarters.
*  Establishing data model relationships.
*  Proficiency in incorporating supplementary data into an existing data model.

# Dashboard: 

[Click Here](https://app.powerbi.com/view?r=eyJrIjoiOTdiZTNlYWMtMjBmYy00MzJkLWIzYmUtY2I3NDkxZmE3NjI2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) to interact with the dashboard 

## Finance View 

![finance-view](https://github.com/user-attachments/assets/998423ef-bde4-4946-b9ad-3680f7e34bae) 

## sales view 

![sales](https://github.com/user-attachments/assets/3076a315-06d0-4d61-ad4b-57a5adec6264)

## marketing view 

![marketing](https://github.com/user-attachments/assets/5a3e67ff-b7dc-49c8-9ce1-364ef2acd7f2)

## supply chain view 

![supply chain](https://github.com/user-attachments/assets/b4d12751-2c8e-4e26-9efa-2509f0f79480)

## executive view 

![executive](https://github.com/user-attachments/assets/6c1884aa-2427-4b2e-8bd9-510df6aa7aa8)








