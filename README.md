1.Black Friday Sales Data Analysis

This project explores the Black Friday Sales dataset to understand customer purchase behavior, demographics, and product trends. The analysis is performed in Python using data visualization libraries like Matplotlib and Seaborn.



2.📊 Dataset

   Source: Black Friday Dataset (Kaggle)

   Rows: 537,577

   Columns: 12

   Features include:

   User_ID

   Product_ID

   Gender

   Age

   Occupation

   City_Category

   Stay_In_Current_City_Years

   Marital_Status

  Product_Category_1

  


3.🛠️ Technologies Used

Python

pandas (data manipulation)

numpy (numerical analysis)

matplotlib & seaborn (visualization)

plotly (interactive charts)


4.🔍 Key Analysis Performed

Gender Analysis: Distribution and total purchase by male vs female customers.

Age Group Analysis: Purchase trends across different age groups.

City Category: Distribution of customers and purchases across cities (A, B, C).

Marital Status: Spending behavior of married vs unmarried customers.

Stay in Current City: How long customers have been staying and its effect on purchases.

Occupation: Purchase distribution by occupation categories.

Product Categories: Purchase behavior across Product Categories 1, 2, and 3.

Top Products: Most frequently bought products and highest revenue-generating products.

5.📈 Visualizations

Some of the insights are shown through:

Pie charts (gender, city category, marital status)

Bar plots (age, occupation, product categories)

Count plots (age by gender, city by age)

Horizontal bar plots (top products by purchase count and amount)

6.🔑 Insights

Male customers dominate the dataset.

Age group 26–35 spends the most.

Customers in City Category B and C contribute higher purchases than City A.

Longer stay in current city correlates with higher purchase amounts.

Product Category 1 generates the highest sales.

A small number of products contribute disproportionately to total revenue.

7.🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/black-friday-analysis.git
cd black-friday-analysis


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook and run the analysis:

jupyter notebook sales-data-analysis-report.ipynb

8.📌 Future Improvements

Build interactive dashboards using Plotly Dash or Streamlit.

Apply machine learning models to predict purchase amount.

Perform customer segmentation (e.g., RFM analysis).
