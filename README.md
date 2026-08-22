# E-Commerce Sales Analysis

A Python-based data analysis project exploring e-commerce sales, profit, product performance, category performance, regional trends, and time-based sales patterns.

## 📌 Project Overview

This project analyzes an e-commerce sales dataset using Python to understand overall business performance and identify meaningful patterns across products, categories, regions, and time periods.

The analysis combines data cleaning, exploratory data analysis, aggregation, profitability analysis, and data visualization to generate actionable business insights and recommendations.

## 🎯 Objectives

- Analyze overall sales, profit, and quantity sold
- Identify the highest- and lowest-performing products
- Compare sales and profitability across categories
- Analyze regional performance
- Identify monthly and yearly sales and profit trends
- Calculate and compare profit margins
- Understand the relationship between sales, profit, and quantity sold
- Perform cross-dimensional analysis across products, categories, regions, and years
- Generate business insights and recommendations

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Anaconda
- Git & GitHub

## 📊 Analysis Performed

### Exploratory Data Analysis

- Dataset structure and dimensions
- Data types and descriptive statistics
- Missing value checks
- Duplicate checks
- Date and time-based analysis

### Product Analysis

- Sales by product
- Profit by product
- Quantity sold by product
- Product profitability
- Profit margin by product
- Sales vs. profit relationship
- Quantity sold vs. sales relationship

### Category Analysis

- Sales by category
- Profit by category
- Quantity sold by category
- Profit margin by category
- Product performance within each category

### Regional Analysis

- Sales by region
- Profit by region
- Quantity sold by region
- Region × Category performance

### Time-Based Analysis

- Monthly sales and profit
- Yearly sales and profit
- Year × Category performance
- Identification of highest- and lowest-performing months and years

### Business Analysis

- Overall business KPIs
- Key business insights
- Final conclusions
- Business recommendations

## 📈 Key Findings

- The business generated total sales of **10.67M** and total profit of **1.84M** from **17,261 units sold**, resulting in an overall profit margin of **17.29%**.
- **Camera** was the strongest-performing product in terms of total sales and profit.
- **Monitor** had the highest quantity sold among the products.
- **Laptop** achieved the highest profit margin at **18.47%**, while Tablet had the lowest profit margin at **16.36%**.
- **Electronics** consistently remained the strongest-performing category across regions and years, leading in sales, profit, and quantity sold.
- **Office** consistently showed weaker performance compared with Electronics and Accessories across regions and years.
- **West** was the strongest-performing region in terms of sales, profit, and quantity sold.
- **2023** was the strongest year in terms of total sales and profit.
- **August 2023** recorded the highest monthly sales.
- **December 2023** recorded the highest monthly profit.
- **February 2024** recorded the lowest monthly sales and profit.
- Higher quantity sold did not always translate into higher sales or profitability, highlighting the importance of evaluating both sales volume and profit margins.

## 💡 Business Recommendations

- **Focus on Electronics:** Electronics consistently leads in sales, profit, and quantity across regions and years, making it the strongest category for continued business focus.
- **Investigate Office category performance:** Office consistently records lower sales, profit, and quantity across regions and years. Its weaker performance should be investigated to identify opportunities for improvement.
- **Prioritize profitable products:** Camera generates the highest total sales and profit, while Laptop has the highest profit margin. Product decisions should therefore consider both revenue contribution and profitability.
- **Monitor sales efficiency:** Higher quantities sold do not always result in higher sales or profit. Monitoring profit margins alongside sales volume can help identify products that generate stronger returns.
- **Investigate the 2024 slowdown:** Sales and profit declined in 2024 compared with 2023, despite quantity sold increasing for Electronics. This warrants further investigation into pricing, product mix, or other factors affecting revenue and profitability.
- **Review seasonal performance:** February 2024 recorded the lowest monthly sales and profit, suggesting a period that may require further investigation for potential seasonal or operational factors.

## 📌 Final Conclusions

- The business generated **10.67M in sales** and **1.84M in profit**, with an overall profit margin of **17.29%**.
- **Camera** was the strongest product by sales and total profit, while **Laptop** had the highest profit margin.
- **Electronics** was consistently the strongest category across products, regions, and years.
- **West** was the strongest-performing region, while **2023** was the strongest year.
- The analysis shows that higher unit volume does not necessarily translate into higher revenue or profitability, making profit margins an important metric for evaluating business performance.

## 📁 Project Structure

- `ecommerce_sales_analysis.ipynb` — Complete analysis notebook
- `ecommerce_sales_data (2).csv` — E-commerce sales dataset
- `.gitignore` — Git ignore configuration
- `README.md` — Project documentation

## 🚀 How to Run

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook or VS Code
- Pandas
- Matplotlib

### Steps

1. Clone this repository.

   `git clone <your-repository-url>`

2. Navigate to the project folder.

   `cd E-Commerce-Sales-Analysis`

3. Install the required libraries if needed.

   `pip install pandas matplotlib jupyter`

4. Open the notebook in Jupyter Notebook.

   `jupyter notebook ecommerce_sales_analysis.ipynb`

   Alternatively, open `ecommerce_sales_analysis.ipynb` directly in VS Code.

5. Make sure `ecommerce_sales_data (2).csv` is present in the same folder as the notebook.

6. Run the notebook cells from top to bottom.

## 📚 Libraries Used

- Pandas — Data manipulation and analysis
- Matplotlib — Data visualization

## 👩‍💻 Author

**Khushi Gupta**

B.Tech CSE Student | Aspiring Data Analyst

---

⭐ This project was built as part of my learning journey in Python and Data Analysis, with a focus on applying Pandas and Matplotlib to a complete end-to-end business analysis.
