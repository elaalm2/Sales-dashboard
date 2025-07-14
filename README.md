# Call Center Analysis - Excel

### Link to [MY LinkedIn](https://www.linkedin.com/in/hakeem-data-analyst/)
### Link to [Download The Dashboard file](https://docs.google.com/spreadsheets/d/1TshA46xfcr-gyRMP8Tm3jguSN5KfBQkd/export?format=xlsx) 

<br>
<div align="center">
    <img width="1335" height="757" alt="Image" src="https://github.com/user-attachments/assets/850d1af0-aef4-4535-8029-aab4807e7b03" />
</div>


## Introduction
<details>
   <summary><strong>📌 Overview (click)</strong></summary>

 ### **Overview**  
> This dynamic Sales Performance Dashboard provides a comprehensive snapshot of key business metrics to help stakeholders monitor performance, identify trends, and drive informed decisions.

> Built using Microsoft Power BI, the report visualizes sales, profit, orders, customer behavior, and product performance across multiple dimensions with interactivity and time intelligence.  

</details>


<details>
   <summary><strong>📂 Data Sources (click)</strong></summary>

### **Data Sources**  
> The primary dataset used for this analysis is the **"Fact_Call_Center"** Sheet containing detailed information about each Call.  

**▼ 📑Dataset Files Explanation** [[Download]](https://raw.githubusercontent.com/ibrahim-saiied/Call_center/refs/heads/main/Data%20Set/Call%20Center%20(Dataset).rar)  


1. **Sales Dataset**  
   > - **<ins>Order ID</ins>**: Unique **ID** for each **Order**. 
   > - **<ins>Amount</ins>**: **Sales Amount or Revenue** for each order.
   > - **<ins>Profit</ins>**: Profit from each order.
   > - **<ins>Quantity</ins>**: Quantity sold of a specific product for each order.
   > - **<ins>Category</ins>**: The Category of the product sold.
   > - **<ins>Sub-Category</ins>**: The Sub-Category of the product sold.
   > - **<ins>PaymentMode</ins>**: The Payment method for the order.
   > - **<ins>Order Date</ins>**: The date when the order was placed.
   > - **<ins>CustomerName</ins>**: The customer who placed the order.
   > - **<ins>State</ins>**: The State from which the customer placed the order.
   > - **<ins>City</ins>**: The City from which the customer placed the order.

</details>

<!-- ------------------------------------------------------------------------------------------- -->

## 🗂️ Case Study
A mid-sized retail company was experiencing stagnant sales growth and needed visibility into their performance across different products, regions, and customer behaviors. Stakeholders lacked a consolidated view of critical KPIs and trends over time.

## 🎯 Objective
> - Build an interactive dashboard that helps business decision-makers:
> - Track overall sales performance and profitability
> - Identify underperforming and overperforming categories and regions
> - Understand the impact of different payment methods on revenue
> - Compare metrics against the previous year using Time Intelligence

## Main 𝐊𝐏𝐈𝐬
- **<ins>Total Sales</ins>**: It is the sum of all Sales amounts for orders sold.
- **<ins>Total profit</ins>**: It is the sum of all Profit gained for orders sold.
- **<ins>Total Orders</ins>**: It is the total number of orders placed. 
- **<ins>AVG Order Value</ins>**: It is the average amount paid by a customer to place a single order.
- **<ins>Profit Margin %</ins>**: It is the percentage of revenue that remains as profit after all expenses are deducted.

## Process
1) Imported, explored and validated the data
2) Cleaned the data using Power Query
3) Created calculated Date table
4) Built a data model
5) Created key measures using DAX 
6) Designed an interactive and insightful dashboard

## Measures (Dax)
;
<img src="https://github.com/user-attachments/assets/62bacb17-9e9d-4412-82b7-8179673d61fc" alt="image" width="320" height="550" style="display: block; margin: 0;">

## Data Model
![image](https://github.com/user-attachments/assets/f7dbc60e-06e8-4cea-a919-f0636b2e7f4a)

## Dashboard
<img width="1500" alt="Group 3" src="https://github.com/user-attachments/assets/dc81c929-aa05-4aab-b525-44d5aa7c4bbd" />
<img width="1500" alt="Group 3" src="https://github.com/user-attachments/assets/1977bd4a-6ebb-496b-bad8-5eeea6e89b35" />
<img width="1500" alt="Group 3" src="https://github.com/user-attachments/assets/0022b20a-be22-4d65-94f3-a061e77ecfe8" />


[![Watch the demo](https://github.com/user-attachments/assets/2509495d-7fbf-4781-88c7-67f0db18b34f)](https://github.com/user-attachments/assets/eeb2cb96-1bd4-416c-8281-7c89d84cdc17)


## Important Insights
 1) **Service Level is On Target**
    - At 92.0%, we’re meeting our goal (91.5%), showing good responsiveness, but we need to keep monitoring performance on certain days.
 3) **Hold Time** 
    - Current hold rate is 10.8%, exceeding the 10% target. Process optimization may help reduce this
 3) **First Call Resolution (FCR)**
    - We achieved 92.1% FCR, which is well above the target (80%). This means most customer issues are solved on the first call a strong sign of quality service.
4) **Answer Rate Needs Improvement**
    - Current rate is 93.2%, slightly below the 95% target. This means we need to improve staffing or efficiency during busy hours.
 5) **Peak Hour is 3–4 PM**
    - The highest call volume occurs between 3:00 and 4:00 PM with over 2,450 calls. This is a key time to ensure strong agent coverage.
 6) **Sunday & Saturday weekends volume & performance**
    - Saturday and Sunday show 100% service level, mainly due to very low call volume and sufficient staffing.
 7) **Customer Inquiries & Resolution Rate**
    - The resolution rate is highest for Tech Support (80.2%) and slightly lower for Billing and Complaints (78–79%).
 8) **Some agents rated below target**
    - A few agents didn’t meet the target in several KPIs like rating, AHT, and hold %. This shows they may need more training or support to improve their performance.












