# Coffee-shop-sales-analysis
**Coffee Shop Sales Analysis** 

**About the Dataset:** 

The dataset used for this analysis was sourced from Maven Analytics and pertains to Maven Roasters, a fictitious coffee shop chain operating across three locations in New York City. The dataset includes transaction records with details such as transaction date, timestamp, store location, and product-level specifics. 

**Data Preview:** 

- **transaction\_id:** A unique sequential ID representing an individual transaction. 
- **transaction\_date**: The date of the transaction (MM/DD/YY). 
- **transaction\_time:** The timestamp of the transaction (HH:MM). 
- **transaction\_qty:** The quantity of items sold. 
- **store\_id:** A unique ID representing the coffee shop where the transaction took place. 
- **store\_location:** The location of the coffee shop where the transaction took place. 
- **product\_id:** A unique ID representing the product sold. 
- **unit\_price**: The retail price of the product sold. 
- **product\_category:** A description of the product category. 
- **product\_type**: A description of the product type. 
- **product\_detail**: A description of the product detail. 

**Data Cleaning Steps:** 

1. **Product Details and Size Separation**: 
- The product\_detail field initially contained both the product description and the size of the product. These were separated into two distinct fields, product\_description and product\_size, to enhance data clarity and enable more detailed analysis. 
2. **Trimming Whitespace from Product Size:** 
- The product\_size field contained leading and trailing spaces, which were removed to ensure data consistency and accuracy during further analysis. 
3. **Extraction of Transaction Time**: 
- The transaction\_time field included an arbitrary date along with the time of the transaction. Since only the time was relevant for the analysis, the date portion was removed, retaining only the time in the transaction\_time field. 
4. **Separation of Month and Day from Date:** 
- To facilitate time-based analysis, the original transaction\_date field was split into separate month and day fields. This allows for a more detailed examination of trends and patterns based on specific months and days. 

**Analysis and Insights:** 

1. **Sales Trends Over Time:** 
- Sales at Maven Roasters displayed distinct patterns, with the quantity of orders peaking between 10-11 AM. The number of orders gradually increased until 10 AM, after which a decline was observed. The highest number of orders was recorded on Mondays, while Fridays generated the highest revenue. 
2. **Busiest Days of the Week:** 
- Monday emerged as the busiest day, marked by the highest number of orders. However, Friday generated the highest revenue, possibly due to larger or higher-value orders. 
3. **Top-Selling Products:** 
- The most frequently sold product was the Barista Espresso, while Drip Coffee was the least ordered. Hot Chocolate generated the highest revenue, while the Scone contributed the least. 
4. **Revenue by Product Category:** 
- The product categories that generated the most revenue were Coffee and Flavors, indicating strong customer preferences for these categories. 
5. **Product Size Popularity:** 
- Regular-sized products were the most commonly ordered, whereas large- sized products generated the most revenue. 
6. **Store Location Performance:** 
- The store located in Hell’s Kitchen recorded both the highest revenue and the highest number of orders, making it the most successful location in the chain. 
7. **Seasonal Trends Analysis (January to June)** 

   **Observations:** 

- **Total Sales:** **January** month observed the highest amount of the sales. 
- **Footfall**: 

  **June** recorded the highest footfall, indicating a peak in customer visits during this month. 

- **Average Revenue Per Person**: 

  **January** exhibited the highest average revenue generated per person, suggesting that individual transactions were of greater value compared to other months. 

- **Average Orders Per Person**: 

  **June** saw the highest average number of orders received per person, reflecting increased purchasing frequency during this month. 

 ![Screenshot 2024-08-21 233551](https://github.com/user-attachments/assets/c1342072-f53d-4011-ba81-6f055ed58156)
![Screenshot 2024-08-21 233531](https://github.com/user-attachments/assets/4158f2b5-018c-4d6b-91aa-2f4cd8afa084)

