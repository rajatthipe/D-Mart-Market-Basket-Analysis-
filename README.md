# 📊 Market Basket Analysis (MBA) – Grocery Store 🛒
### Overview
* This project uses the Apriori algorithm to perform Market Basket Analysis on transactional data. It identifies frequent itemsets and derives association rules that can help optimize product placement, marketing strategies, and bundling offers.

## 🔍 Key Insights & Findings
### ✅ Frequent Itemsets:
* Top-selling combinations were identified using support thresholds.

### ✅ Association Rules:
* Rules like {"whole milk"} ➝ {"yogurt"} with high confidence were discovered, suggesting strong purchase relationships.

### ✅ Transaction Analysis:
* 50% of transactions contained ≤4 items, while the largest had 32 items – indicating most purchases are small but there’s potential in bulk-buying customer segments.

### ✅ One-Hot Encoding:
* Transactions were transformed into a binary matrix for algorithm compatibility using TransactionEncoder.

## 📈 Visualizations
* Bar plots of frequent itemsets 🧱

* Support vs Confidence vs Lift scatter plots 📐

* Heatmaps and pair plots for item correlation 🎨

### 💡 Suggestions for Improvement
##### 📌 Include Data Source:
* The dataset loading is missing (e.g., no read_csv present). Please ensure the data is either added or linked for reproducibility.

##### 📌 Parameter Tuning:
* Explore a wider range of min_support and min_confidence values to generate more diverse rules.

##### 📌 Interactive Dashboard:
* Consider using Plotly or Streamlit for an interactive visualization experience.

##### 📌 Performance Optimization:
* Add runtime metrics to track performance for large datasets.
