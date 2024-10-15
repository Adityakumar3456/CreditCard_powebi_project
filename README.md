
## **README: Credit Card Transaction Report Dashboard**

### **Project Overview**

This Power BI dashboard provides a comprehensive analysis of credit card transaction data, offering insights into key metrics such as revenue, total transactions, interest earned, and transaction count. It allows for detailed exploration of transaction patterns based on various customer attributes and card characteristics.

### **Data Sources**

* **[List of data sources used]** 
  * Example: `credit_card.csv`, `customer(1).csv`

### **Data Preparation**

* **Data Cleaning:**
  * Handled missing values, outliers, and inconsistencies in the data.
  * Corrected data types and formatting errors.
* **Data Enrichment:**
  * Created new columns:
    * **Revenue:** Calculated based on transaction amount and fees.
    * **Age Type:** Categorized age ranges (e.g., Young Adult, Middle Age, Senior).
    * **Salary Type:** Categorized salary levels (e.g., Low, Medium, High).

### **Dashboard Components**

* **Key Performance Indicators (KPIs):**
  * Total Revenue
  * Total Transactions
  * Total Interest Earned
  * Average Transaction Value
* **Visualizations:**
  * **Revenue Analysis:**
    - Revenue by Education Level
    - Revenue by Experience Type
    - Revenue by Customer Job
    - Revenue by Card Category
    - Revenue by Chip Used
  * **Transaction Analysis:**
    - Total Transactions by Quarter
    - Sum of Revenue by Quarter
    - Card Category Comparison (Revenue, Total Transactions Earned, Interest Earned, Count of Transactions)
  * **Customer Segmentation:**
    - Customer Segmentation by Age Type and Salary Type
    - Customer Lifetime Value Analysis


### **Snap of Dashboard**
![Dashboard](https://github.com/user-attachments/assets/433b32dd-19af-4a7c-8dcc-ecbb7dba3589)


### **How to Use**

1. **Open the Power BI report file.**
2. **Explore the dashboard components:** Interact with visualizations to gain insights into different aspects of the credit card transaction data.
3. **Use filters and slicers:** Apply filters to drill down into specific segments of the data.
4. **Export data or create custom reports:** If needed, export data or create custom reports based on your specific requirements.

### **Technical Details**

* **Power BI Desktop version:** 2.136.1478.0
* **Data model:**  snowflake schema
* **Measures and calculations:** Added Revenue Column using Interest, Fees, Total_trans_amount. Made a new Column Age Type and salary type. Done some calculations on week tables, Current week revenue and previous week revenue. At last created a dashboard.

### **Limitations and Considerations**

* **Data quality:** The accuracy and completeness of the results depend on the quality of the underlying data.
* **Data privacy:** Ensure compliance with data privacy regulations when handling sensitive customer information.
* **Data refresh:** If data sources are updated regularly, configure automatic data refresh to keep the dashboard up-to-date.

### **Contact**

* Name:- Adityakumar Pal 
*  Email:- ap704257@gmail.com 

### **Additional Notes**

* **Version control:** Consider using version control tools (e.g., Git) to track changes to the dashboard.
* **Documentation:** Maintain clear and concise documentation to explain the design, functionality, and usage of the dashboard.
* **User feedback:** Gather feedback from users to identify areas for improvement and ensure the dashboard meets their needs.

**By following these guidelines, you can create a valuable and informative credit card transaction report dashboard that provides actionable insights for your organization.**
