# 🪔 Diwali Sales Analysis

**A data analytics case study identifying the customer segments that drive Diwali-season retail sales, using Python for data cleaning, exploratory analysis, and visualization.**

## 📌 Business Problem

A retail business ran a Diwali sales campaign and collected 11,000+ customer transactions but had no clear picture of **who its customers actually are** or **what drives revenue**. This project analyzes that raw transaction data to answer three questions a business stakeholder would ask:

1. Which customer demographics generate the most revenue?
2. Which regions and product categories should marketing and inventory prioritize?
3. Who is the ideal customer profile to target in future campaigns?

## 🧠 Skills Demonstrated

- **Data Cleaning** — handling nulls, dropping irrelevant fields, fixing data types
- **Exploratory Data Analysis (EDA)** — segmenting data across demographics, geography, and product lines
- **Data Visualization** — communicating patterns clearly with Seaborn/Matplotlib charts
- **Business Insight Generation** — translating raw numbers into an actionable customer profile and recommendation
- **Python for Data Analysis** — Pandas for data manipulation, NumPy for computation

## 📂 Dataset

The dataset (`Diwali Sales Data.csv`) contains **11,251 transaction records** across **15 columns**, including:

| Column | Description |
|---|---|
| `User_ID` | Unique customer identifier |
| `Cust_name` | Customer name |
| `Product_ID` | Unique product identifier |
| `Gender` | Customer gender |
| `Age Group` / `Age` | Customer age bracket and exact age |
| `Marital_Status` | 0 = Unmarried, 1 = Married |
| `State` / `Zone` | Customer's location |
| `Occupation` | Customer's profession |
| `Product_Category` | Category of the purchased product |
| `Orders` | Number of orders placed |
| `Amount` | Transaction value (₹) |

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — data cleaning and manipulation
- **NumPy** — numerical operations
- **Matplotlib** & **Seaborn** — data visualization
- **Jupyter Notebook** — interactive analysis environment

## 🔍 Analysis Workflow

1. **Data Cleaning**
   - Removed irrelevant/blank columns (`Status`, `unnamed1`)
   - Handled missing values
   - Corrected data types (e.g., `Amount` cast to integer)

2. **Exploratory Data Analysis**
   Analysis was broken down across key dimensions:
   - **Gender** — purchase count and total spend by gender
   - **Age** — spending patterns across age groups
   - **State** — top 10 states by order volume and revenue
   - **Marital Status** — spend comparison between married and unmarried customers
   - **Cross-analysis** — combining dimensions (e.g., marital status × gender) to sharpen the customer profile
   - **Occupation** — top spending professions
   - **Product Category** — best-selling categories and top products

## 💡 Key Insights

| Dimension | Finding |
|---|---|
| Gender | **Women** account for the majority of purchases and show **higher spend per customer** than men |
| Age | The **26–35** age group is the most active buying segment |
| Location | **Uttar Pradesh, Maharashtra, and Karnataka** lead in both order volume and total revenue |
| Marital Status | **Married customers**, especially Married women, generate more total revenue than unmarried customers |
| Occupation | Buyers are concentrated in **IT Sector, Healthcare, and Aviation** |
| Product Category | **Food, Clothing & Apparel, and Electronics & Gadgets** generate the most revenue |

### 🎯 Recommendation
The data points to a clear target customer: **Married women, aged 26–35, in Uttar Pradesh/Maharashtra/Karnataka, working in IT, Healthcare, or Aviation, shopping for Food, Clothing, and Electronics.** Concentrating marketing spend and inventory planning on this profile would improve ROI for future Diwali campaigns.

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Run the analysis
```bash
git clone https://github.com/shiveshmukund/Python_Diwali_Sales_Analysis.git
cd Python_Diwali_Sales_Analysis
jupyter notebook Diwali_Sales_Analysis.ipynb
```

## 📁 Repository Structure

```
├── Diwali_Sales_Data.csv          # Raw dataset
├── Diwali_Sales_Analysis.ipynb    # Full EDA notebook (cleaning, visualization, insights)
└── README.md                      # Project documentation
```

## 🙏 Acknowledgements

Dataset sourced for educational/portfolio purposes to practice EDA and data visualization techniques.

## 📬 Connect With Me

- [LinkedIn](https://linkedin.com/in/shiveshmukund)   
- [Portfolio](https://shiveshmukund.github.io/Portfolio_Website/)

---

⭐ If you found this project useful, consider giving it a star!
