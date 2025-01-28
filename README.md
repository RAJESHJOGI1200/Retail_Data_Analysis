# Retail Data Analysis Project

## 📊 Project Overview
This project involves analyzing retail transaction data to uncover insights and provide actionable recommendations for business strategies. The project focuses on customer segmentation, sales trends, and product performance analysis to support strategic planning for the next half-year.

## 🚀 Key Objectives
- Clean and preprocess retail transaction data.
- Conduct exploratory data analysis (EDA) to identify trends and patterns.
- Segment customers by **lifestage** and **premium category**.
- Analyze product preferences, sales performance, and pricing trends.
- Provide actionable insights and recommendations for business growth.

---

## 🗂️ Project Tasks and Workflow

### **1. Data Exploration**
- **Datasets Used**:
  - `QVI_transaction_data.xlsx`: Contains transaction details such as date, store number, product quantity, total sales, and product names.
  - `QVI_purchase_behaviour.csv`: Contains customer information, including lifestage and premium category.
- Explored data structure, summary statistics, and checked for missing or inconsistent values.
- Converted date columns to proper datetime format and removed irrelevant data (e.g., salsa products).

---

### **2. Data Cleaning and Feature Engineering**
- Removed outliers, such as transactions where customers purchased 200 packs in a single transaction.
- Extracted **pack size** and **brand name** from product names.
- Consolidated similar brand names for consistency (e.g., "RED" to "RRD", "SNBTS" to "SUNBITES").
- Merged transaction and customer datasets using `LYLTY_CARD_NBR` as the key.

---

### **3. Exploratory Data Analysis**
- **Sales Analysis**:
  - Grouped sales by `LIFESTAGE` and `PREMIUM_CUSTOMER` to identify high-performing segments.
  - Calculated total sales, average units purchased per customer, and average price per unit for each segment.

- **Product Preferences**:
  - Identified popular brands and pack sizes by segment.
  - Calculated brand and pack size affinity for the "Young Singles/Couples - Mainstream" segment compared to others.

---

### **4. Visualizations**
Created the following visualizations to support insights:
1. **Total Sales by Lifestage and Premium Customer**:
   - Bar plot comparing sales across customer segments.
2. **Average Units Purchased**:
   - Bar plot showing the average number of units purchased per customer segment.
3. **Average Price per Unit**:
   - Bar plot visualizing pricing differences by customer segment.

All visualizations were created in Python using `matplotlib` and `seaborn`.

---

## 📌 Key Insights
1. **Top Spending Segments**:
   - Older families in the **Budget** category spend the most on chips.
   - Young singles/couples in the **Mainstream** category show unique preferences.

2. **Brand and Pack Size Preferences**:
   - Young Singles/Couples in the **Mainstream** segment have a high affinity for premium brands like Doritos and pack sizes of 270g and 380g.

3. **Price Sensitivity**:
   - Budget segments show lower average price per unit, indicating price sensitivity compared to premium customers.

---

## 💡 Recommendations
1. **Target Marketing**:
   - Focus promotional campaigns on **Older Families - Budget** and **Young Singles/Couples - Mainstream** segments to drive sales.

2. **Optimize Inventory**:
   - Stock high-affinity brands and pack sizes (e.g., Doritos and 270g/380g packs) in stores catering to the **Mainstream** segment.

3. **Dynamic Pricing**:
   - Consider offering discounts or loyalty programs to retain **Budget** segment customers while maintaining margins.

---

## 🛠️ Tools and Technologies
- **Python**: Data cleaning, analysis, and visualizations.
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`.
- **Excel**: For data visualization exports.
- **GitHub**: Version control and collaboration.

---

## 📂 Folder Structure
Retail_Data_Analysis/ ├── QVI_transaction_data.xlsx # Transaction dataset ├── QVI_purchase_behaviour.csv # Customer dataset ├── retail_data_analysis.ipynb # Jupyter notebook with code ├── README.md # Project documentation └── visualizations/ # Folder for graphs and charts


---

## 📞 Contact
If you have any questions or would like to discuss the analysis further, feel free to reach out.

- **Name**: Rajesh Jogi
- **Email**: rajeshjogi1200@gmail.com
- **GitHub**: [RAJESHJOGI1200](https://github.com/RAJESHJOGI1200)

---

Let me know if you’d like to make any changes to this! 🚀
