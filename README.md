# Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge

## Created & Analyzed by Saddam Ansari @Aspiring Data Analyst [Linkedin](https://www.linkedin.com/in/saddam-ansari-dataanalyst/)


## Challenge Objective:
This project is part of the **FP20Analytics challenge**, focusing on analyzing **fuel price trends in Argentina** over recent years. Through data collection from various sources such as government databases and fuel companies, the project aims to uncover patterns of price adjustments, seasonal trends, and regional differences. 

The analysis provides insights into factors influencing fuel price changes without complex statistical methodologies, focusing on gasoline, diesel, and alternative fuels to offer a comprehensive overview of price variations across Argentina.

## Detailed Description of Dataset:

For this project, stakeholders have provided a dataset spanning from 2016 to 2023, capturing fuel prices across Argentina. The dataset comprises approximately 34,753 rows of data.

 * **Date Range**: The dataset covers the period from 2016 to 2023.
 * **Company ID (Seller)**: There are 4414 unique values representing different sellers.
 * **Company Name (Fuel Pump Name):** There are 3383 unique values for company names.
 * **City:** There are 1045 unique cities represented in the dataset.
 * **Province:** The dataset includes data from 24 unique provinces.
 * **Region:** Data is categorized into 6 unique regions.
 * **Product ID and Type:** There are 5 distinct values for product IDs and types.
 * **Shift Type:** Shifts are categorized as daytime and nighttime, with 2 unique values.
 * **Price:** Prices range from a minimum of 7 pesos to a maximum of 159 pesos.
 * **Flag Company:** There are 7 unique values in this column.

## Project Overview:

This data analysis project was developed in response to the project request, which guided the creation of two main pages within the dashboard.

### Home Page:

The Home page serves as the gateway to the dashboard, offering an overview of key insights. It features interactive slicers and filters for user customization, allowing stakeholders to explore data based on their preferences.

### Insights Page:

The Insights page serves as the heart of the dashboard, presenting visually appealing insights with detailed explanations for stakeholders. It provides stakeholders with a user-friendly and easy-to-understand view of the data, enabling them to gain valuable insights effortlessly.

## Detailed Explanation
### Home Page

![Screenshot 2024-03-26 100137](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/467de7ed-c58a-4f18-ad0b-80ad9390ef54)

### Key Performance Indicators (KPIs):
 * Gross Sales(Total price): $11.2M Argentina Pesos
 * Overall avg price: $327.1
 * Total Product type: 5
 * Total Flag Company: 10
 * Total Sellers(petrol pump): 4309
#

### Sales Year and Month

The "Sales Year and Month" visual provides valuable insights into car sales trends over different years and months. This visual allows stakeholders to observe sales patterns by year initially, with the flexibility to drill down to specific months within each year for a more detailed analysis.

#### Insight-
Upon analysis, it becomes evident that the **year 2023 witnessed the highest sales**, **totaling 11.04 million pesos**. This sales figure constitutes a significant portion, accounting for 98.08% of the total sales during the specified period. This highlights the remarkable performance of car sales in 2023 compared to other years.

#

### Is shift type affects the gross total price and average price of fuel?. 
To explore this, a donut charts have been created by me, allowing stakeholders to easily observe the shift-wise gross total sales and average prices.

#### Insight:

Upon analyzing the data, it appears that there is no notable variance in average fuel prices between daytime and nighttime shifts. However, a marginal difference of 0.1% is observed in total sales. Specifically, there were 1430 pesos more sales during the daytime shift compared to the nighttime shift. This suggests that while average prices remain consistent, there is a slight difference in total sales between the two shifts, with daytime sales marginally higher than nighttime sales.


#

### Sales by flag company, 

visualized using a ZoomChart. This visual enables stakeholders to easily observe the sales generated by each company, with the option to drill down by fuel type.

#### Insight:

 * Upon analysis, it is evident that YPF flag company has recorded the highest sales, totaling 4.2 million pesos, representing 37.36% of the total sales. 

 * Conversely, Sin Empresa bandera flag company has the lowest sales, amounting to only 82.4 pesos. This highlights the significant difference in sales performance among different flag companies, with YPF leading the market and Sin Empresa lagging behind significantly.

#

### Top 10 cities by sales:

I found that Cordoba city has the highest sales, amounting to 474.1K pesos, with an average price of 338.2 pesos. This indicates the significant contribution of Cordoba city to overall sales, highlighting its prominence in the fuel market.

#

### Flag Company Market Share Analysis

Insight:
Upon analysis, it is evident that YPF holds the highest market share, commanding a significant portion of the total market at 34.08%. This dominance is further emphasized by the presence of approximately 1.5K sellers and fuel pumps associated with YPF, indicating its extensive reach and influence in the fuel industry.

#

## Insight Page ( Stakholders and Insights)

#### Request 1- What is the average price of Gasoil Grade 2 across all provinces?

![1](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/16e714a7-c149-4d6b-9796-6b5d81b60390)

#### Request 2- Which company has the highest total sales by city?

![2](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/43adbfd5-2cd3-4008-ab4f-b1b79e9b10d7)

 * The company with the highest total sales by city is  YRF, with sales of $4.2M Argentine pesos, constituting 37.36% of the total sales. Its highest sales occurred in the Capital Federal city, amounting to 184K pesos.

 * The second company by total sales is Shell CAPSA, with total sales of 2.6M pesos, representing 23.59% of the total. Its highest sales were in Cordoba city, amounting to 158.9K pesos.

For further insights into other companies, visual drilldowns are available.

#### Request 3- How has the price of Petrol Premium - 95 Octane changed from September 2023 to October 2023?

![3](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/85936b0d-9599-4e6a-8e6d-508db4aca80c)

The price of Petrol Premium - 95 Octane witnessed a positive change from September 2023 to October 2023.  

In September 2023, the sales of Petrol Premium - 95 Octane were recorded at 117k, whereas in October 2023, the sales surged to  2362k(2.3M), indicating a remarkable growth of 1925%.

#### Request 4- Which region has the highest average price for Compressed Natural Gas

![4](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/64beec7a-15e1-496f-9398-f58213be99b4)

In the Centro region, the average price of Compressed Natural Gas is highest at 164 pesos, whereas in  Patagonia, it's lowest at 110 pesos.

#### Request 5- Can we observe any significant difference in fuel prices between daytime and nighttime shifts?

![5](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/96a0bc31-e7e3-453c-9fe7-7efb5246ef4b)

Based on average prices, there is no significant difference between daytime and nighttime shifts. 

However, in terms of total sales, there is a minor difference of 0.1%, with 1430 pesos more sales occurring during the daytime shift compared to the nighttime shift

#### Request 6-  What is the price range for Petrol unleaded - 95/98 Octane in the Buenos Aires province?

![6](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/6427d173-847a-4c7e-9917-30353162aa59)

In the Buenos Aires province, the price range for Petrol unleaded - 95/98 Octane exhibits a considerable spread, ranging from 18.8 pesos to 569.2  pesos. 


#### Request 7- How many different types of products are sold by the company "AUTOMOVIL CLUB ARGENTINO"?

![7](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/4815befa-846c-4414-b229-57ea17710f68)

The company "AUTOMOVIL CLUB ARGENTINO" sells a total of 5 different types of products. 

#### Request 8. - Which city in the Patagonia region has the highest recorded price for any fuel type?

![8](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/97ed0b71-87dc-4786-8826-89d47fb67c65)

In the Patagonia region, "NEUQUEN" city has the highest recorded price for any fuel type.  

Gasoil Grad 3 in "NEUQUEN" city has both the highest total sales, standing at 21.3k, and the highest average price of 393.6 pesos. 


#### Request 9- What are the top 10 companies by sales revenue in 2023?

![9](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/8a5d683a-a942-4559-bb32-8009cf8a69ed)

#### Request 10- What is the total revenue generated by each flagged company if we assume each price corresponds to one sale?

![10](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/e85b02f4-335e-4680-99ef-883cd2354628)

The flagged company YRF generated the highest total revenue, amounting to 12.90k, which accounts for 37.13% of the total revenue.

#### Request 11- Which company experienced the greatest percentage change in the price of Gasoil Grade 3 between September 2023 and October 2023?

![11](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/cd00ec8b-4026-4bae-8d70-8ae6477d05c0)

The company that experienced the greatest percentage change in the price of Gasoil Grade 3 between September 2023 and October 2023 is Puma. Puma recorded the highest percentage growth, showing an astonishing 3561% increase during this period.

#### Request 12- .What was the highest and lowest prices of Gasoil Grade 2 in the province of Buenos Aires during the year 2023?

![12](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/b071f387-4651-4de6-a8ef-7caaf06ab0c2)

The highest price of Gasoil Grade 2 in the province of Buenos Aires during the year 2023 was 543.9 pesos, while the lowest price recorded was 177 pesos.

#### Request 13- Which month had the greatest profit win in the prices of Petrol unleaded - 95/98 Octane during the year 2022?

![13](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/4a7cdad4-6b42-474d-9b0c-b4961e837b98)

#### Request 14- What was the product that showed the highest sales?

![14](https://github.com/user-saddam123/Argentina-National-fuel-Market-Analysis-FP20-Analytics-Mar-2024-Challenge/assets/123800896/53f2d216-09e8-445b-8b0f-9a046ae79ea4)

The product that showed the highest sales was Gasoil Grad 3, with total sales amounting to 3.1 million pesos, representing 27.87% of the total  sales.

Conversely, the product with the lowest sales was Compressed Natural Gas, with sales amounting to 495.1k pesos, which accounts for 4.34% of the total sales.

#
## Conclusions:
Based on the analysis conducted as part of the FP20Analytics challenge, several insights have been derived regarding the fuel market in Argentina from 2016 to 2023. This project serves to provide stakeholders with a comprehensive understanding of fuel price trends, market dynamics, and the performance of various companies operating in the sector. The following conclusions can be drawn from the analysis:

 * **Sales Trends:** The analysis reveals that 2023 marked the highest sales year, indicating a significant uptrend in car sales. This insight is crucial for stakeholders, highlighting the need for strategic planning and resource allocation to capitalize on growing market demand.

 * **Shift Impact on Sales:** While there is little difference in average fuel prices between daytime and nighttime shifts, a marginal variance in total sales suggests a potential area for further investigation. Understanding the underlying factors contributing to this difference could help stakeholders optimize sales strategies based on shift timings.

 * **Flag Company Performance:** YPF emerges as the dominant player in the market, capturing the highest market share and generating substantial revenue. Conversely, the analysis identifies companies with lower sales performances, signaling opportunities for improvement or strategic partnerships to enhance market presence.

 * **Regional Disparities:** Variations in fuel prices across provinces and regions underscore the importance of localized market strategies. Stakeholders can leverage this information to tailor pricing and marketing approaches to specific regional dynamics, maximizing profitability and market penetration.

 * **Product Performance:** Gasoil Grad 3 emerges as the top-selling product, indicating strong demand within the market. Understanding product preferences and demand dynamics is essential for stakeholders to optimize product offerings and inventory management strategies.

 * **Price Fluctuations:** Significant price fluctuations, such as the remarkable growth in the sales of Petrol Premium - 95 Octane from September to October 2023, highlight the volatility of the market. Stakeholders need to monitor and analyze price trends to adapt pricing strategies effectively and maintain competitiveness.

#

## How this insights helps to our stakholders?
This project not only provides valuable insights into the fuel market but also enhances stakeholders' decision-making processes. By leveraging data-driven analysis, stakeholders can identify growth opportunities, mitigate risks, and optimize operational efficiency within the fuel industry. 

## My learnings
Additionally, this project has enabled me, as an aspiring data analyst, to gain hands-on experience in data visualization, trend analysis, and stakeholder communication, thereby enhancing my analytical and communication skills in a real-world context.

#

#### This project is the result of over 9 days of hard work, and I invite you to 👍 like, share, and connect with me on LinkedIn. [LinkedIn Link](https://www.linkedin.com/in/saddam-ansari-dataanalyst/)
I hope scrolling through this project provides you with insightful understanding.

Thank you for taking the time to view my project.

#

Created and Presented by-

Saddam Ansari @Aspiring Data Analyst [LinkedIn Link](https://www.linkedin.com/in/saddam-ansari-dataanalyst/)

Location: India

### THE END



