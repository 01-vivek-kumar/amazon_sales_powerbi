# 📊 Amazon Sales Dashboard: Power BI Project



## 🟢 1. Data Ingestion & Loading
- Imported the sales dataset into Power BI.
- Verified the dataset structure and checked the headers for understanding.

## 🔍 2. Data Understanding
- Analyzed dataset fields, including order details, product information, and sales records.
- Identified key columns for analysis, such as `Order Date`, `Sales`, `Product`, `Market`, and `Returned`.

## 🧹 3. Data Cleaning & Transformation
1. **Extracted Year:** Created a new column by extracting the year from the `Order Date` to analyze sales trends by year.  
2. **Mapped Returned Column:** Replaced `Yes` and `No` values in the `Returned` column with `1` and `0` for easier calculations.  
3. **Removed Nulls:** Cleaned null values from critical fields to ensure accurate reporting.  
4. **Calculated Delivery Days:** Created a new metric for `Delivery Days` by subtracting `Order Date` from `Ship Date`.  

---

## 📏 4. Key Metrics Calculated
Using **DAX**, I calculated the following key performance indicators (KPIs):  
- 💰 **Total Sales:** Sum of all sales transactions.  
- 📦 **Products Sold:** Count of unique products sold.  
- 🔄 **Returns:** Total returned products based on the mapped `Returned` column.  
- 📊 **Average Quantity Sold:** Average quantity of products sold per order.  

---

## 📊 5. Visualizations Created
To present the insights effectively, I used the following visuals:  

1. **Sales by Segment:** Displayed using a **Pie Chart**.  
2. **Sales by Market:** Used a **Doughnut Chart** for regional sales distribution.  
3. **Top 10 Customers by Sales:** Showcased as a **Clustered Bar Chart**.  
4. **Top 5 Products by Profit:** Highlighted using a **Bar Chart**.  
5. **Bottom 5 Products by Profit:** Visualized to identify less profitable products.  

---

## 🔍 Key Insights & Recommendations

### 📈 1. **Sales Trend**
- **Insight:** Sales consistently increased from **2012 to 2015**, reflecting business growth.  
- **Recommendation:** Leverage historical trends to set higher sales targets for future years. Focus on peak seasons and regions driving the growth.  

### 👥 2. **Segment Contribution**
- **Insight:** The **Consumer segment** contributes an average of **50% to total sales** each year.  
- **Recommendation:** Maintain focus on consumer-driven campaigns while exploring strategies to boost sales in the **Corporate** and **Home Office** segments. Personalized offers or bundling might encourage higher engagement.  

### 🛒 3. **Top Purchasers**
- **Insight:** A few top purchasers significantly drive sales.  
- **Recommendation:** Implement a **customer loyalty program** to retain these high-value customers. Regularly share product recommendations based on past purchases.  

### 🌟 4. **Product Performance**
- **Top 5 Products:** High-selling products contribute significantly to revenue.  
  - **Recommendation:** Ensure optimal inventory levels for these products and prioritize them in marketing campaigns.  
- **Bottom 5 Products:** Underperforming products indicate low demand.  
  - **Recommendation:** Consider discounting or discontinuing these items. Investigate if product awareness, pricing, or availability is affecting sales.  

### 🚚 5. **Operational Efficiency**
- **Insight:** Delivery time (calculated from order to ship date) can be optimized.  
- **Recommendation:** Collaborate with logistics partners to streamline the supply chain, ensuring faster deliveries and higher customer satisfaction.  

### 🌍 6. **Market Strategy**
- **Insight:** Sales performance varies across markets.  
- **Recommendation:** Prioritize high-performing markets while developing targeted marketing campaigns for underperforming regions.  

---

## 📈 Final Thoughts
This project helped me uncover valuable insights into sales performance, product trends, and operational efficiency. The **Amazon Sales Dashboard** not only highlights top-performing areas but also points out opportunities for improvement.  

For more details, check out my GitHub repository! 🚀
