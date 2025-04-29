# fmcg-sales-analysis
Power BI and Python-based analysis of FMCG sales and inventory with predictive modeling and hypothesis testing.

## 📊 Dataset Overview
5,000+ transactions with details on:
- **Sales**: Units sold, revenue, profit, discount
- **Product & Customer**: Category, brand, age group, region
- **Inventory & Supply Chain**: Stock levels, supplier reliability
- **Marketing**: Spend, competitor prices, pricing differences

## 🧠 Key Analyses
- **Power BI Dashboard**: Interactive visuals for product sales, channel performance, pricing effectiveness, and customer segmentation
- **Statistical Testing**:
  - **Level-log regression**: Stock levels vs. discounts
  - **ANOVA**: Impact of competitor price difference on profits
- **Predictive Modeling**:
  - CART Decision Tree for profit forecasting
  - **R² = 0.998**, highlighting potential overfitting and the need for further model tuning

## 💡 Business Insights
- Higher price difference over competitors is significantly associated with higher profit margins
- Discounts negatively impact stock levels; other expected drivers like marketing spend were not statistically significant
- Recommendation: Prioritise “positive difference” products for promotion

## 🛠 Tools Used
- Power BI
- Python (Pandas, Sklearn, Seaborn, Statsmodels)
- Jupyter Notebook

## 📂 Files
- `project 2 powerbi final file.pbix` – Power BI report
- `Final_project_3.ipynb` – Statistical testing & modeling in Python
- `Project 2 presentation.pdf` – Final slides summarizing insights

## 👤 Author
Vidhi Sikarwar | Economics Undergraduate | Ashoka University
