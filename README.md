# Product-Sales-Analysis
Real-world product sales data analyzed using Python. Includes data cleaning, KPI extraction, and business insights with visualizations.

This project is a real-world sales data analysis conducted using Python in Google Colab. It includes full data cleaning, KPI tracking, and actionable business insights based on visualizations and trend analysis.

---

## 📁 Dataset Overview

The dataset used is `Product-Sales-Region.xlsx` and contains 1500 rows and 19 columns.

### Key Columns:
- `OrderDate`, `DeliveryDate`, `Region`, `Product`, `TotalPrice`
- `Quantity`, `Discount`, `Returned`, `ShippingCost`, `PaymentMethod`
- `CustomerType`, `Salesperson`, `Promotion`, `RegionManager`

---

## 🧪 Environment

- Google Colab
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- OpenPyXL (for Excel support)

---

## 📌 Analysis Workflow

1. **Import Libraries**  
2. **Read Excel File & Inspect Structure**  
3. **Data Cleaning**
   - Checked for nulls, datatypes, duplicates
   - Converted dates and numeric columns
   - Handled missing TotalPrice
4. **Feature Engineering**
   - Delivery time (in days)
   - Monthly sales trends
5. **KPI Calculation & Charts**
6. **Business Insights & Recommendations**

---

## 📊 Visualizations

### 📍 Total Sales by Region  
A bar chart showing the revenue performance across different regions.

<img width="914" height="449" alt="image" src="https://github.com/user-attachments/assets/4cc9bc34-8614-43cd-b6cd-080f64f2e2df" />

---

### 📍 Monthly Sales Trend  
Shows how sales progressed month by month.

<img width="943" height="390" alt="image" src="https://github.com/user-attachments/assets/cfee4a3e-3252-4afc-b8f3-6fe77e25104e" />

---

### 📍 Top 10 Products by Revenue  
Identifies which products bring in the most revenue.

<img width="947" height="439" alt="image" src="https://github.com/user-attachments/assets/98c3075e-b9c2-4d3e-9df7-8c69655a346a" />

---

### 📍 Return Rate (%)  
Shows how often products are returned and the difference between returned and not returned.

<img width="824" height="368" alt="image" src="https://github.com/user-attachments/assets/c9a8ddd1-ca74-491a-9d31-da6a5ca01f68" />

---

### 📍 Sales by Payment Method  
A pie chart of the most common customer payment methods.

<img width="593" height="401" alt="image" src="https://github.com/user-attachments/assets/0da03992-2f08-49d2-af14-4bb2726c51fa" />

---

## 📈 Key KPIs Calculated

| KPI | Value |
|-----|-------|
| ✅ Average Delivery Time | ~6.04 Days |
| ✅ Return Rate | ~8.6% |
| ✅ Total Sales | Sum of TotalPrice |
| ✅ Best Performing Region | Highest sales volume |
| ✅ Most Used Payment Method | Digital (Credit/UPI) |

---

## 💡 Business Insights

1. **Top Regions Perform Better**  
   → Use winning strategies in low-performing regions.

2. **Returns vs Discounts**  
   → High discounts may lead to more returns. Balance offers smartly.

3. **Best Products Identified**  
   → Focus marketing on bestsellers.

4. **Digital Payments Preferred**  
   → Cash is becoming rare – ensure smooth digital payments.

5. **Sales Peaks Monthly**  
   → Target promo campaigns around high-sales months (e.g. holidays/festivals).

6. **Delivery Delays = More Returns**  
   → Fix logistics in areas with delays to reduce returns.

---

## ✅ Final Recommendations

- 📦 Promote best-selling products, phase out slow movers.
- 🌍 Focus on underperforming regions with potential.
- 🚚 Improve delivery in areas with long shipping times.
- 🛍️ Provide better product descriptions and images to reduce returns.
- 📅 Plan major discount campaigns around high-traffic months.


## 👤 Author

**Ashish Jha**  
[LinkedIn](www.linkedin.com/in/ashish-jha-aj885829)  
📧 aj885829@gmail.com
