 # Project Background
This project was done using a synthetic dataset of a fictional online video game store that saw an increase in revenue during the pandemic year of 2020. The objective is to analyze the data to uncover insights that can improve the company's commercial performance.

Insights and recommendations are provided on the following key areas:

- Sales Trends Analysis: Evaluation of historical sales patterns, focusing on Revenue, Order Volume, and Average Order Value.
- Product-Level Performance: An Analysis of the products sold by the store, to understand their impact on sales.
- Marketing Channels Comparison: An Evaluation of sales and orders by marketing channel.
- Regional Comparison: An Evaluation of sales and orders by region.

An interactive PowerBI dashboard can be viewed [here](https://app.powerbi.com/view?r=eyJrIjoiMTc5YTM0NDktOTMyOS00NjU0LWFhODQtY2JiMWZlNDZlOTNjIiwidCI6ImU0NmQzODYyLTg1OTUtNDVkMS05YjY5LTYzMDc5OGQ4OTAyZCIsImMiOjR9).

The Power Query steps utilized to clean and prepare data for the dashboard can be found here.

# Data Structure & Initial Checks

The database structure as seen below consists of two tables: orders and regions, with a total row count of 8,093 records.

![Structure](/img/Structure.png)

Prior to beginning the analysis, several quality control checks were performed to ensure data integrity and familiarize myself with the dataset. The steps used to perform the quality checks can be found [here](Data%20cleaning%20and%20preparation.md).

# Executive Summary

## Overview of Findings

After peaking in the second half of 2020, the company's sales have declined significantly, even below pre-pandemic numbers. All three Key Performance Indicators have shown year-over-year decreases: Total sales by 85.2%, average order value by 7.5% and order volume by 84%. While the rise of 2020 and the decline of 2021 can be attributed to the shift in consumers' habits during the COVID-19 pandemic, the following sections will explore additional contributing factors and highlight key areas for improvement.

Below are the main metrics from the PowerBI dashboard, with more examples included throughout the report.

![KPIS](/img/InitialKPIS.png).


### Sales Trends

- **The Company's Sales peaked on December 2020 with 394 orders totaling  $136,067.19 monthly revenue.** This corresponds to with the worldwide boom of consumer spending in leisure activities done within households due to the pandemic. 
- As soon as 2021 started, **revenue declined on a year over year basis throughout the period.** So much so that it reached the company lifetime low in March 2021, with earnigs of just over $11.6K. In the following months, while there was a slight recovery, earnings were still below even pre-pandemic numbers.  
- Average Order Value (AOV) saw intermittent year-over-year increases, with a **lifetime high in June 2021 of $405.65 per order.** Driven primarily by high ticket products such as the Sony Playstation Bundle and the 24-inch 4K gaming monitor. 
- As for the order volume, there was a significant decrease throughout 2021, with a **lifetime low of 46 orders in April 2021.** 

[IMG]

### Product Perfomance:

- **More than 85% of the company's orders come from three products**, the Nintendo Switch, the 24-inch 4k gaming monitor and the JBL Quantum Gaming Headset. These generated $130.5K in revenue in 2021, accounting for 61% of total revenue.
- The underperforming product is the Acer Nitro V Gaming Laptop, contributing to less than 1% in total orders despite being, on average, $300 cheaper than the Lenovo Ideapad Gaming 3 Laptop.
- As for the share of orders, the **leading products throughout all three years are the Nintendo Switch and the 24-inch 4K gaming monitor, accounting for ~50% and ~20% of sales respectively** on a monthly basis. 
- The company is reliant on the revenue provided by three products, the 24-inch 4k gaming monitor, the Nintendo Switch and the Sony Playstation 5 bundle. All of which accounted for **85% of the total revenue of 2021.** However, the PS5 bundle registered only 4.7% of orders.

[IMG]

### Marketing Channels:

- The direct channel maintained its importance throughout 2021, with it's **80% revenue share and 77% order share.**
- While sales across all channels follow the same downward trend, the average order value increased in 2021 for the affiliate and email channels. With affiliate having achieved an **AOV of $564.89, 70% above social media, the lowest performer.**
- Despite having a good performance in the previous metric, the affiliate channel accounts for only 1.5% of total orders, the same as social media, suggesting it is primarily associated with high-ticket products.

[IMG]

### Regions:

- While North America continues to hold the largest share, with 44% of the total revenue and 50% of order share, EMEA (Europe, the Middle East, and Africa) and APAC (Asia-Pacific) outperformed North America in revenue on the months from March up to June 2021 due to large ticket products such as the 24-inch 4K Gaming Monitor and the Playstation 5 Bundle.
- After 2020, **all regions except APAC saw a decrease in average order value, with North America having largest decline by 14%.** The difference between APAC ($368.29) and NA ($264.23) being of 28%.

[IMG]

## Recommendations

Based on the uncovered insights, the following recommendations have been provided:

- The EMEA region has potential for high ticket products. The company should consider developing targeted campaigns for high-income segments and Prioritize premium product bundles (console + monitor + headset).
- The company is highly dependent on three products for 85% of revenue. To diversify the revenue stream, it is recommended to develop cross-sell and upsell strategies (e.g., accessories + warranties) and expand mid-range product offerings. 
- The Nintendo Switch consistently accounts for ~50% of sales each month. A potential strategy could be to look into other Nintendo products like accesories and video game cartridges. 
- Marketing has a big focus on the direct channel, so to avoid overreliance we could look into strategies for the other ones.
- For the low impact products such as the Acer Nitro V Gaming Laptop and the Dell Gaming Mouse, it would be worth to check on reviews and overall sentiment towards these products to check if it would be worth to continue offering them or try to come up with bundle repositioning  of laptop + gaming mouse + headset at a value price.
- To stabilize revenue after a pandemic-driven demand, the company could look into implementing loyalty rewards for repeat purchases, send post-purchase emails promoting accesories and launching limited-time offers targeting past buyers.
