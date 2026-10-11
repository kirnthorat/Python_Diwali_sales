# 🪔 Diwali Sales Analysis using Python

Exploratory data analysis (EDA) of Diwali sales data to understand customer behavior and find ways to improve customer experience and sales during the festive season.

## 📌 Project Overview

Diwali is one of India's biggest shopping seasons. This project analyzes **11,251 transactions** (about **₹10.6 crore** in total sales) to answer questions like:

- Who are the biggest buyers by gender, age group, and marital status?
- Which states and zones generate the most sales?
- Which occupations and product categories drive revenue?

## 🗂️ Repository Structure

```
Python_Diwali_sales/
├── Diwali Sales Data.csv          # Dataset
├── Diwali_Sales_Analysis.ipynb    # Analysis notebook
└── README.md                      # Project documentation
```

## 📊 Dataset

| Column | Description |
|---|---|
| User_ID | Unique customer ID |
| Cust_name | Customer name |
| Product_ID | Unique product ID |
| Gender | Male / Female |
| Age Group | Age bracket (e.g., 18-25, 26-35) |
| Age | Customer age |
| Marital_Status | 0 = Unmarried, 1 = Married |
| State | Customer's state |
| Zone | Region of India |
| Occupation | Customer's profession |
| Product_Category | Category of product purchased |
| Orders | Number of orders |
| Amount | Purchase amount (₹) |

> The columns `Status` and `unnamed1` were completely empty and were dropped.

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** and **NumPy** for data cleaning and analysis
- **Matplotlib** and **Seaborn** for visualization
- **Jupyter Notebook**

## 🔄 Workflow

1. **Data loading:** read the CSV file with Pandas
2. **Data cleaning:** dropped empty columns, removed null values (12 rows with missing `Amount`), and fixed data types
3. **Exploratory analysis:** analyzed sales by gender, age group, marital status, state, zone, occupation, and product category
4. **Visualization:** built count plots and bar plots to show patterns
5. **Conclusions:** summarized findings and recommendations

## 💡 Key Insights

- **Gender:** Women contributed about **70%** of total sales.
- **Age group:** Customers aged **26-35** were the biggest spenders, at about **40%** of sales.
- **Location:** **Uttar Pradesh, Maharashtra, and Karnataka** were the top 3 states by sales amount.
- **Occupation:** **IT, Healthcare, and Aviation** professionals were among the top buyers.
- **Product category:** **Food, Clothing & Apparel, and Electronics & Gadgets** were the top-selling categories.

## ✅ Conclusion

Married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the most valuable customers. They mainly buy products in the Food, Clothing, and Electronics categories.

## 🎯 Recommendations

- Focus festive campaigns on women aged 26-35 in the top states.
- Increase stock of high-demand categories (Food, Clothing, Electronics) before Diwali.
- Run targeted offers for IT, Healthcare, and Aviation professionals.

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/kirnthorat/Python_Diwali_sales.git
cd Python_Diwali_sales

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch the notebook
jupyter notebook Diwali_Sales_Analysis.ipynb
```

> If you see an encoding error while reading the CSV, use `pd.read_csv("Diwali Sales Data.csv", encoding="unicode_escape")`.

## 🚀 Future Improvements

- Build an interactive Power BI dashboard on this dataset
- Add customer segmentation and sales forecasting
- 
## 👤 Author

**Kiran Thorat**
Data Analyst | Pune, India
📧 thoratk1107@gmail.com
💻 GitHub: [github.com/kirnthorat](https://github.com/kirnthorat)
🔗 LinkedIn: www.linkedin.com/in/kiranthorat878
