# AtliQ hardware-Dashboard



## Problem Statement
AtliQ Hardware, a company operating in the hardware industry, is experiencing challenges in conducting comprehensive sales analysis for the period 2017 to 2020. The company is unable to gain clear insights into key aspects of its sales performance, including identifying high-value customers, understanding non-supportive customer segments, analyzing profit margins, and evaluating revenue trends

Recognize that revenue experienced a noticeable decline in 2020 compared to previous years. 

Difficulty in identifying the reasons for the company's decline compared to previous years and recognizing specific markets that need more focus for improvement.


### Steps followed 

Step 1: Imported the dataset into MySQL, performed data fetching to understand its structure, and identified invisible duplicate rows with differing values.

Step 2: Loaded the dataset, consisting of 1126 rows, into Power Query and applied basic transformations like removing duplicates and fixing errors

Step 3: Cleaned the dataset by resolving inconsistencies and ensuring data accuracy for reliable analysis.

Step 4: Analyzed sales data to identify high-value customers and non-supportive customer segments within the company’s sales records.

Step 5: Examined profit margins, revenue trends, top 5 revenue-generating customers, and revenue contributions by markets.

Step 6: Created bar charts, line charts, and tables to effectively visualize sales insights and provide a clear presentation.

Step 7: Integrated slicers into the visualizations to enable filtering by year and month for dynamic exploration of sales patterns.

(a). Delhi has the highest revenue, while Bengaluru has the lowest.  

(b). Brick & mortar customers make up 84.43%, and e-commerce is 15.57%.  

(c). Total profit margin is ₹24.7M.  

(d). Top 5 customers are Electricalsara Store, Electricalslytical, Excel Stores, Premium Stores, Nixon.  

(e). Bhubaneshwar contributes 10.5% profit, while Lucknow incurs a -2.7% loss.  

(f). Mumbai contributes 23.9% profit, while Lucknow is at -0.6%.  

(g). Delhi accounts for 54.7% revenue, while Bhubaneshwar is at 0.1%.  

(h). Electricalsbea Store contributes 15.6% revenue, while Electricalsquipo Store shows -11.5%.  

(i). The average profit margin across markets is 2.53%.  

(j). Revenue trends show Delhi leading, while Bhubaneshwar lags significantly.  

(k). High-value customers drive sales, while non-supportive customers need addressing.  
  


  


for creating dax for Profit contribution in perecntage
       
       Profit Margin contribution% = DIVIDE([Total Profit margin]
       ,CALCULATE([Total Profit margin],ALL('sales customers'),ALL('sales products'),ALL('sales markets')))
        
Snap of profit contribution in perecntage,

![Image](https://github.com/user-attachments/assets/087880b2-eb39-474f-a887-74142b718ff4


 I calculated the average profit margin as 
 2.53%, providing insights into
 overall profitability.

![Image](https://github.com/user-attachments/assets/2fde8845-07a8-4b9a-8a66-d7106247e669)

(a) Calculated total revenue, revenue trends, and revenue contribution by market and customer.

(b)Determined profit margins, including average profit and profit contributions by markets.

(c) Analyzed high-value and non-supportive customers and identified the top 5 revenue-generating customers. 

(d)Created visual insights for revenue and profit analysis using slicers for better filtering.  

        Revenue contribution% = DIVIDE([Revenue],CALCULATE([Revenue],ALL('sales customers'),ALL('sales products')
        ,ALL('sales markets')))

 # Report Snapshot (Power BI DESKTOP)

Profit Analysis


![Snap](https://github.com/user-attachments/assets/f45662b7-0965-4f58-8f33-2af39b0db5f6.PNG)



Key Insights

![Snap](https://github.com/user-attachments/assets/6baeed55-9a35-4b69-b44d-b5dbbd5a8e13.PNG)

# AtliQ hardware-Dashboard.md.txt
Displaying # AtliQ hardware-Dashboard.md.txt.
