# 🧹 Project 1: Data Cleaning & Preparation

## 📌 Description
This project focuses on cleaning a raw e-commerce dataset by handling missing values, removing duplicates, and correcting data formats. Clean data is the foundation of any reliable analysis.

## 📂 Files
| File | Description |
|------|-------------|
| `ecommerce_raw_messy.csv` | Raw dataset with intentional issues |
| `ecommerce_clean.csv` | Cleaned output dataset |
| `project_1_data_cleaning.ipynb` | Full cleaning notebook |

## 🔍 What Was Cleaned
- ✅ Filled 313 missing `CouponCode` values with `NO_COUPON`
- ✅ Removed 19 duplicate rows
- ✅ Removed 15 invalid date entries
- ✅ Removed 10 negative price entries
- ✅ Standardized `Product` column (trim + proper case)

## ▶️ How to Run
```bash
# 1. Install required libraries
pip install pandas numpy matplotlib seaborn jupyter

# 2. Open the notebook
jupyter notebook project_1_data_cleaning.ipynb

# 3. Run All cells
```

## 🛠️ Tools Used
- Python, Pandas, NumPy, Jupyter Notebook
