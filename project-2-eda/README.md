# 🔍 Project 2: Exploratory Data Analysis (EDA)

## 📌 Description
This project analyzes the clean e-commerce dataset to uncover hidden patterns, trends, and outliers. The goal is to transform raw numbers into actionable business insights.

## 📂 Files
| File | Description |
|------|-------------|
| `project_2_eda.ipynb` | Full EDA notebook |
| `distribution_analysis.png` | Price & quantity distributions |
| `outlier_detection.png` | Boxplot outlier analysis |
| `monthly_trend.png` | Monthly revenue trend |
| `product_performance.png` | Revenue by product |
| `correlation_matrix.png` | Correlation heatmap |
| `status_payment.png` | Order status & payment analysis |

## 📈 Key Findings
- 💰 Total Revenue analyzed across 1,177 orders
- 📦 Top performing products identified
- 📅 Monthly revenue trends visualized
- 🔎 Outliers detected using IQR method
- 📊 Right-skewed price distribution → Median better than Mean for pricing strategy

## ▶️ How to Run
```bash
# 1. Make sure Project 1 is completed first (needs ecommerce_clean.csv)

# 2. Install required libraries
pip install pandas numpy matplotlib seaborn jupyter

# 3. Open the notebook
jupyter notebook project_2_eda.ipynb

# 4. Run All cells
```

## 🛠️ Tools Used
- Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
