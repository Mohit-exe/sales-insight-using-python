# 🛒 Black Friday Sales Data Analysis
---
A data analysis project on the **Black Friday Sales dataset** using Python, Pandas, Matplotlib, and Seaborn.  
This project explores customer purchase behavior based on demographics and product categories.

---

## 📂 Project Overview
This project provides insights into:
- Customer demographics (gender, age, marital status, city category, occupation).
- Purchase patterns by age group, gender, and city category.
- Popular product categories.
- Spending behavior across different customer segments.

---

## 📊 Dataset
- **Source:** Black Friday Sales dataset (`BlackFriday.csv`)  
- **Size:** ~500,000 rows  
- **Features:**
  - `User_ID`, `Product_ID`
  - `Gender`, `Age`, `Occupation`, `City_Category`, `Stay_In_Current_City_Years`, `Marital_Status`
  - `Product_Category_1`, `Product_Category_2`, `Product_Category_3`
  - `Purchase` (amount spent)

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

---

## 📈 Key Insights
- **Males** form a higher proportion of buyers compared to females.
- Age group **26–35 years** contributes the most to purchases.
- **City Category B** shows the largest sales contribution.
- Customers with **longer stay in cities (4+ years)** tend to spend more.
- **Product Category 1** has the highest sales, followed by **Product Category 2**.
- Top products contribute significantly to overall revenue.

---

## 🖼️ Visualizations
The analysis includes:
- Pie charts for gender, city category, marital status, and stay years distribution.
- Bar plots for purchases across demographics and occupations.
- Horizontal bar charts for product category purchases.
- Top 10 most purchased and most revenue-generating products.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/black-friday-sales-analysis.git
2. Navigate into the project folder
   ```bash
   cd black-friday-sales-analysis
3.Install required libraries.
  ```bash
   pip install -r requirements.txt
```
4.Run the Jupyter notebook.
  ```bash
jupyter notebook sales-data-analysis-report.ipynb
```

## 📌 Future Improvements
Here are some enhancements planned for this project:
- Machine Learning Models – Build predictive models to forecast purchase amounts and customer behavior.
- Interactive Dashboards – Use Plotly Dash or Streamlit to create dynamic dashboards for real-time analysis.
- Data Cleaning Enhancements – Handle missing values and outliers more efficiently for better accuracy.
- Feature Engineering – Create new features like customer loyalty scores, frequency of purchase, or product affinity.
- Recommendation System – Suggest personalized products to users based on their purchase history.
- Scalability – Extend the analysis to larger retail datasets for broader applicability.
- Deployment – Package the analysis as a web app so it can be accessed without running Jupyter Notebook.








