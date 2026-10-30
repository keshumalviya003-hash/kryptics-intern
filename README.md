# 🛒 Big Mart Sales Analysis using Python

## 📌 About the Project

This is my first Data Analysis project using Python. In this project, I worked on the Big Mart Sales dataset to understand product sales and find useful insights from the data.

My main goal was to explore the data, clean it, identify patterns, and understand how different factors affect sales.

## 📂 About the Dataset

The dataset contains information about different products and outlets of Big Mart.

It includes two CSV files:

- **Train.csv:** Contains product and outlet information along with Item Outlet Sales.
- **Test.csv:** Contains product and outlet information without the sales column.

For this project, I mainly worked with the Train dataset.

### Important Columns

| Column               | Description                 |
| -------------------- | --------------------------- |
| Item_Identifier      | Unique product ID           |
| Item_Weight          | Weight of the product       |
| Item_Fat_Content     | Fat content of the product  |
| Item_Visibility      | Visibility of the product   |
| Item_Type            | Category of the product     |
| Item_MRP             | Maximum Retail Price        |
| Outlet_Identifier    | Unique outlet ID            |
| Outlet_Size          | Size of the outlet          |
| Outlet_Location_Type | Location type of the outlet |
| Outlet_Type          | Type of outlet              |
| Item_Outlet_Sales    | Sales of the product        |

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 What I Did in This Project

Here are the steps I followed during my analysis:

1. Loaded the dataset using Pandas.
2. Explored the data using `head()`, `tail()`, `info()` and `describe()`.
3. Checked missing values and handled them.
4. Checked duplicate records.
5. Analyzed numerical columns using summary statistics.
6. Checked data distribution and skewness.
7. Identified outliers using the IQR method.
8. Analyzed categorical columns using value counts.
9. Created different visualizations to understand sales patterns.
10. Studied the relationship between numerical and categorical columns.

## 📊 Visualizations Created

I created different charts to understand the dataset better:

- Sales Distribution Histogram
- Sales Outlier Boxplot
- Item Type Distribution
- Average Sales by Item Type
- Average Sales by Outlet Type
- Average Sales by Outlet Size
- Average Sales by Outlet Location Type
- Average Sales by Item Fat Content
- MRP vs Sales Scatter Plot
- Numerical Columns Correlation Heatmap

## 💡 Key Findings

After completing the analysis, I found some interesting things:

- Most products have lower sales, while a few products have very high sales.
- Fruits and Vegetables and Snack Foods are among the most common item categories.
- Supermarket Type3 has the highest average sales.
- Grocery Stores have the lowest average sales.
- Medium-sized outlets show higher average sales than Small and High-sized outlets.
- Tier 2 outlets have slightly higher average sales.
- Item MRP has a positive correlation with Item Outlet Sales.
- Different fat content categories have almost similar average sales.

## 📁 Project Structure

```text
Big-Mart-Sales-Analysis/
│
├── Train.csv
├── Train.ipynb
└── README.md
```

## 🎯 What I Learned

While working on this project, I improved my understanding of Pandas, NumPy, data cleaning, missing value handling, outlier detection, and data visualization.

I also learned how to explore a real-world dataset and find meaningful insights from it.

## 🙌 Conclusion

This project helped me understand how Exploratory Data Analysis (EDA) works in real-world projects. It was a good learning experience for me, and I got practical experience working with Python and data visualization.

**Thanks for checking out my project!** 😊

