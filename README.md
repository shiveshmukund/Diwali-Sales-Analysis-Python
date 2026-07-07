# 🪔 Diwali Sales Analysis

**Exploratory data analysis of 11,000+ festive-season transactions to uncover who buys, what they buy, and where the revenue comes from.**

---

## 📌 Overview

Retailers running a festive sale need to answer three practical questions fast: **who is buying, what are they buying, and where should inventory go next?**

This project analyzes a retail dataset of **11,251 Diwali-season transactions** across 16 Indian states to answer exactly that. Using Python, the raw data is cleaned, explored, and visualized to surface actionable patterns in customer demographics and product performance — the kind of insight a business team could use to plan inventory, target marketing, and improve customer experience for the next sales cycle.

---

## 🎯 Business Questions Answered

- Which gender and age group drives the most purchases and revenue?
- Which states generate the highest order volume and sales value?
- Does marital status influence spending behavior?
- Which occupations are most represented among high-spending customers?
- Which product categories and individual products sell the most?

---

## 🗂️ Dataset

| Detail | Value |
|---|---|
| Source file | `Diwali_Sales_Data.csv` |
| Raw records | 11,251 rows × 15 columns |
| Records after cleaning | 11,239 rows × 13 columns |
| Fields | Customer ID, Name, Gender, Age, Age Group, Marital Status, State, Zone, Occupation, Product Category, Product ID, Orders, Amount |
| Total revenue analyzed | ₹10.62+ crore (₹106,249,129) across 27,981 orders |

---

## 🛠️ Tools & Libraries

- **Python** — core analysis
- **Pandas / NumPy** — data cleaning, transformation, aggregation
- **Matplotlib / Seaborn** — statistical visualization
- **Jupyter Notebook** — end-to-end, reproducible workflow

---

## 🔍 Project Workflow

### 1. Data Cleaning
- Handled encoding issues on import (`unicode_escape`)
- Dropped fully empty/irrelevant columns (`Status`, `unnamed1`)
- Removed rows with missing values
- Corrected data types (e.g., cast `Amount` to integer for accurate aggregation)

### 2. Exploratory Data Analysis
Segmented the cleaned data across five lenses to build a complete customer and product profile:
- **Gender** — purchase count and total spend
- **Age Group** — purchase count and total spend, split by gender
- **State** — order volume and revenue by top-performing states
- **Marital Status** — spending patterns by marital status and gender
- **Occupation & Product Category** — where the money is coming from, and where it's going

---

## 📊 Key Insights

- **Gender drives the majority of both purchases and revenue.** Female customers placed the majority of orders (7,832 vs. 3,407) and also accounted for the higher share of total revenue — a clear signal for where marketing and merchandising should be weighted.

- **26–35 age group is the core customer base.** This age band placed the most orders and generated the highest revenue of any group (~₹4.25 crore), making it the primary segment to design promotions around.

- **Sales are concentrated in a handful of states.** Uttar Pradesh, Maharashtra, and Karnataka led both order volume and revenue by a wide margin — useful for regional inventory and logistics planning.

- **Women lead spending across both marital groups.** Whether married or unmarried, female customers outspent male customers in every marital-status segment — reinforcing gender as the strongest spending signal in the dataset, ahead of marital status.

- **IT, Healthcare, and Aviation professionals spend the most.** These three occupations generated the highest cumulative revenue, indicating where higher-value customers are concentrated.

- **Food, Clothing, and Electronics dominate revenue.** These three categories are the clear top performers, well ahead of the remaining 15 categories — the first place to prioritize stock for the next sale.

- **A small set of SKUs drives disproportionate order volume.** The top 10 products by order count highlight exactly which SKUs to keep well-stocked heading into the next festive cycle.

---

## 💡 Recommendations

- **Prioritize female customers, especially aged 26–35**, in campaign targeting and personalized offers — they are both the most frequent and highest-spending segment.
- **Concentrate inventory and logistics investment** in Uttar Pradesh, Maharashtra, and Karnataka, which together account for a disproportionate share of revenue.
- **Stock up early on Food, Clothing & Apparel, and Electronics** ahead of the next festive season, since these three categories consistently outsell the rest.
- **Design occupation-aware offers** (e.g., for IT, Healthcare, and Aviation professionals) who show higher purchasing power.

---

## 🧠 Skills Demonstrated

- Data cleaning and preprocessing (handling nulls, encoding issues, type correction)
- Exploratory Data Analysis (EDA) using Pandas
- Data visualization and storytelling with Matplotlib and Seaborn
- Translating raw transactional data into business-relevant, decision-ready insights
- End-to-end analysis workflow in a single reproducible Jupyter Notebook

---

## 📁 Repository Structure

```
diwali-sales-analysis/
│
├── Diwali_Sales_Data.csv          # Raw dataset (11,251 transactions)
├── Diwali_Sales_Analysis.ipynb    # Full analysis: cleaning, EDA, visualizations
└── README.md
```

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/<your-username>/diwali-sales-analysis.git
cd diwali-sales-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook Diwali_Sales_Analysis.ipynb
```

---

⭐ If you found this project useful or interesting, consider giving it a star!
