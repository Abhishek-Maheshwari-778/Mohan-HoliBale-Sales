# Mohan-HoliBale-Sales
I create and  complete this project using "ChatGPT".
# 🎉 Mohan HoliBale Sales Data Visualization Dashboard

This project showcases an interactive **Power BI Dashboard** created to analyze and optimize Holi sales trends for *Mohan HoliBale*, a business specializing in Holi-related products.

---

## 📄 Project Overview

- **Objective:**  
  Analyze two years of Holi sales data to identify trends, optimize inventory, and boost sales during the festive season.

- **Key Features:**  
  - 📈 Monthly Sales Trends  
  - 🌍 Regional Sales Performance  
  - 🎁 Promotion Effectiveness Analysis  
  - 🏆 Top-Selling Products Visualization  
  - ⭐ Customer Feedback Insights  
  - 💳 Payment Mode Distribution

---

## 📊 Dataset Description

The dataset contains **1,000 rows** and **15 columns** with the following details:

| Column Name           | Description                                |
|-----------------------|--------------------------------------------|
| `Date`                | Day of the sale (1-31)                     |
| `Month`               | Month of the sale                          |
| `Year`                | Year of the sale (2023, 2024)              |
| `Product_ID`          | Unique identifier for each product         |
| `Product_Name`        | Name of the Holi product                   |
| `Category`            | Product category (Colors, Accessories, Sweets) |
| `Quantity_Sold`       | Number of units sold                       |
| `Price_Per_Unit`      | Price per unit (in INR)                    |
| `Total_Sale_Amount`   | Total sales amount (Quantity × Price)      |
| `Region`              | Sale region (North, South, East, West)     |
| `Customer_Age_Group`  | Age group of the customer                  |
| `Customer_Gender`     | Gender of the customer                     |
| `Promotion_Used`      | Type of promotion (Discount, Buy1Get1, None) |
| `Payment_Mode`        | Payment mode (Cash, UPI, Card)             |
| `Feedback_Rating`     | Customer feedback rating (1-5)             |

---

## 🚀 How to Use

1. **Download the Dataset**  
   [Download the dataset](./mohan_holibale_sales.csv)

2. **Open Power BI**  
   - Import the CSV file.  
   - Use the Power BI dashboard to create visualizations.  

3. **Suggested Visualizations**

   - **Line Chart**: Monthly Sales Trends (`Month` vs `Total_Sale_Amount`)  
   - **Donut Chart**: Category-wise Sales Distribution (`Category` vs `Total_Sale_Amount`)  
   - **Clustered Column Chart**: Regional Sales (`Region` vs `Total_Sale_Amount`)  
   - **Stacked Bar Chart**: Customer Demographics (`Customer_Age_Group` and `Customer_Gender`)  
   - **Slicers**: Enable filters for `Year`, `Month`, `Region`, `Promotion_Used`, and `Category`.

---

## ⚙️ Problems, Solutions, and Insights

### 🛑 **Problems Identified**

1. **Unclear Sales Trends:**  
   Difficulty in identifying peak and low sales months for better inventory management.  
   ![Sales Trends](https://github.com/Abhishek-Maheshwari-778/Mohan-HoliBale-Sales/blob/main/a.png)

2. **Ineffective Promotions:**  
   Uncertainty about which promotions (e.g., Discounts or Buy1Get1) are most effective in driving sales.  
   ![Promotion Analysis](https://github.com/Abhishek-Maheshwari-778/Mohan-HoliBale-Sales/blob/main/a2.png)

3. **Regional Sales Disparity:**  
   Lack of understanding about which regions contributed most to sales.  
   ![Regional Sales](https://github.com/Abhishek-Maheshwari-778/Mohan-HoliBale-Sales/blob/main/a4.png)

4. **Product Popularity:**  
   No clear visibility on which products are best-selling versus low-performing.  
   ![Product Popularity](https://github.com/Abhishek-Maheshwari-778/Mohan-HoliBale-Sales/blob/main/a5.png)

5. **Customer Demographics:**  
   Limited knowledge about the primary customer base (age groups, gender) to tailor marketing strategies.  
   ![Customer Demographics](https://github.com/Abhishek-Maheshwari-778/Mohan-HoliBale-Sales/blob/main/a6.png)

### ✅ **Solutions Implemented**

- **Trend Analysis:** Created **Line Charts** showing monthly and yearly sales trends to highlight peak sales periods.
- **Promotion Analysis:** Built **Stacked Column Charts** to evaluate the effectiveness of different promotions on total sales.
- **Regional Insights:** Designed **Clustered Column Charts** to compare sales performance across different regions.
- **Product Ranking:** Developed **Top 10 Product Bar Charts** to focus on best-selling products for better inventory planning.
- **Demographic Analysis:** Used **Stacked Bar Charts** to analyze sales distribution across different age groups and genders.

### 💡 **Key Insights Gained**

- Identified peak sales months to optimize inventory.
- Analyzed the effectiveness of promotions to boost sales.
- Gained insights into regional preferences and customer demographics.

---

## 🛠️ Tools & Technologies

- **Power BI** for data visualization.  
- **Python (Pandas, NumPy)** for data generation.  
- **CSV** for dataset storage.

---

## 📚 Learning & Takeaways

- Gained expertise in creating interactive dashboards.  
- Improved skills in data analysis and storytelling with visuals.  
- Learned how promotions and regional differences affect sales performance.

---

## 🤝 Let's Connect!

Have questions or feedback? Want to collaborate on data visualization projects?  
📧 Reach out at: `temporarypass9@gmail.com`

---

## ⭐ Show Your Support

If you found this project helpful, please consider giving it a ⭐ star!

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
