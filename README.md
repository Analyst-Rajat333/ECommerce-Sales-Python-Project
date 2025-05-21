# 🛒 ECommerce Sales Python Project – Superstore Data Analysis

This project performs a complete **Sales and Profit Analysis** using Python on a real-world eCommerce Superstore dataset. It explores sales trends, product category performance, sub-category breakdowns, customer segments, and profitability over time.

---

## 📦 Dataset Overview

- 📁 File: `Sample - Superstore.csv`
- 🔢 Rows: 9,994 transactions
- 🧾 Features:
  - Order info: Date, Ship Mode, Customer, Region
  - Product info: Category, Sub-Category, Product Name
  - Sales details: Sales, Quantity, Discount, Profit

---

## 🛠 Technologies Used

- **Python 3**
- **Pandas, NumPy** – Data handling
- **Matplotlib, Seaborn** – Visualizations
- **Calendar** – Date formatting
- **Jupyter Notebook** – Analysis & charts

---

## 📊 Project Workflow

1. **Importing and Cleaning Data**
   - Date columns converted to datetime
   - New columns created: `Order Month`, `Order Year`, `Day of Week`

2. **Monthly Sales Analysis**
   - Found highest sales month: **November 2017 – ₹118,447.82**
   - Lowest sales month: **February 2014 – ₹4,519.89**
  ![monthly_sales_by_year](https://github.com/user-attachments/assets/33b6b992-eeaa-49f6-9557-464f06c31ee8)
  ![total_monthly_sales_all_years](https://github.com/user-attachments/assets/3ec42f78-bd40-45fc-b1f9-bd415cc08356)


3. **Sales by Category**
   - 📈 Highest: **Technology – ₹836,154**
   - 📉 Lowest: **Office Supplies – ₹719,047**
   ![category_sales_with_labels](https://github.com/user-attachments/assets/731bb1d0-252f-47f6-8d4e-9e4b23e15a4c)


4. **Sales by Sub-Category**
   - 📈 Highest: **Phones – ₹330,007**
   - 📉 Lowest: **Fasteners – ₹3,024**
   ![sub_category_sales_chart](https://github.com/user-attachments/assets/8ebd62ff-d8cd-4b91-a3aa-2f18c0035fc5)


5. **Monthly Profit Analysis**
   - 📈 Highest profit month: **December – ₹43,369**
   ![monthly_profit_chart](https://github.com/user-attachments/assets/d20235f3-7208-42f1-b321-f435708515ee)


6. **Profit by Category & Sub-Category**
   - 📈 Highest profit: **Copiers (Technology) – ₹55,617**
   - 📉 Lowest profit: **Tables (Furniture) – ₹-17,725**
   ![profit_by_category_subcategory](https://github.com/user-attachments/assets/585b82e2-e16c-42c0-b6bd-a4eeea8c63ae)


7. **Segment-wise Analysis**
   - Most sales: **Consumer Segment**
   - Highest profit margin: **Home Office – 14.03%**
   ![segment_sales_profit](https://github.com/user-attachments/assets/fddba26d-dbed-41f8-af26-d73546909cc9)


8. **Sales to Profit Ratio by Category**
   - Furniture has the **worst ratio (40.21)** despite high sales
   - Technology & Office Supplies are more profitable
   ![sales_to_profit_ratio_by_category](https://github.com/user-attachments/assets/fa9fd8b2-aad4-4b61-a18a-941227009b7b)


---

## 📈 Summary of Insights

- 📆 **November** is consistently the best month for sales.
- 🛍️ **Technology** is the most lucrative category, especially **Copiers** and **Phones**.
- 📉 **Furniture Tables** are a loss-making sub-category.
- 👤 **Home Office segment** has the highest profit margin.
- 📊 Strategic focus should go to **Tech products** during **Q4** for maximized revenue and profit.

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Analyst-Rajat333/ECommerce-Sales-Python-Project.git
