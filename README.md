# 📦 E-commerce Return Rate Analysis

This project analyzes the return rate of products in an e-commerce dataset to uncover key insights, identify influential factors, and help businesses reduce return rates and optimize performance.

## 📁 Repository Structure

```
Final-Project-Ecommerce-return-rate-analysis/
│
├── 📂 dataset/                # Contains the raw and cleaned dataset
│   └── E-Commerce Dataset.csv
│
├── 📂 images/                 # Output visualizations and plots
│
├── 📜 Final_project.ipynb     # Main Jupyter Notebook with complete analysis
├── 📜 README.md               # Project overview and documentation
└── 📜 .gitignore              # Files and directories to ignore in version control
```

---

## 📊 Problem Statement

Returns in e-commerce can significantly impact profitability and logistics. This project aims to analyze return behavior based on various customer and product attributes to identify patterns and reasons behind high return rates.

---

## 🔍 Key Objectives

* Analyze customer demographics, order details, and product information.
* Understand the distribution of returned vs. non-returned products.
* Identify key features influencing return probability.
* Use visualizations to communicate findings clearly.

---

## 🧰 Tools & Technologies

* **Python** (Pandas, NumPy, Seaborn, Matplotlib)
* **Jupyter Notebook**
* **EDA (Exploratory Data Analysis)**
* **Data Cleaning & Preprocessing**
* **Visualization Techniques**

---

## 📈 Exploratory Data Analysis

The notebook includes:

* Missing value treatment
* Univariate and bivariate analysis
* Correlation heatmaps
* Return rate comparison across categories (e.g., product group, gender, delivery time)

---

## 📌 Key Insights

* Certain product groups and delivery delays are associated with higher return rates.
* Female customers tend to return more products than male customers.
* Products with longer delivery times have a higher probability of being returned.

---

## 📷 Sample Visualizations

* Distribution plots of age, delivery time, and product prices
* Return rate by product group
* Correlation heatmaps of numeric features

> 📁 Visuals are saved in the `images/` directory.

---

## 📂 Dataset

The dataset is stored in `dataset/E-Commerce Dataset.csv` and contains fields like:

* `customer_id`
* `product_group`
* `gender`
* `order_date`
* `delivery_time`
* `return` (target variable)

---

## ✅ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/shubham2182/Final-Project-Ecommerce-return-rate-analysis.git
   ```
2. Open the Jupyter Notebook:

   ```bash
   cd Final-Project-Ecommerce-return-rate-analysis
   jupyter notebook Final_project.ipynb
   ```
3. Run all cells to reproduce the analysis.

---

## 📌 Conclusion

This analysis provides valuable insights into the factors that affect product returns in an e-commerce business. It can serve as a foundation for predictive modeling or operational decision-making to reduce returns and improve customer satisfaction.


