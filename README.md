# Customer Segmentation with K-Means

## Overview
This project uses K-Means clustering to segment customers based on income, spending behavior, purchase activity, and recency. It combines data cleaning, feature engineering, exploratory data analysis, and unsupervised machine learning to identify customer groups for data-driven marketing strategies.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Algorithm:** K-Means Clustering
- **Environment:** Google Colab / Jupyter Notebook

## Project Workflow
- **Data Cleaning:** Inspected missing values, analyzed data, and removed duplicates.
- **Feature Engineering:** Created `Total_Spending` and `Total_Purchases`.
- **EDA:** Visualized income, spending, purchases, and feature correlations.
- **Feature Scaling:** Standardized selected features using `StandardScaler`.
- **Clustering:** Used the Elbow Method and applied K-Means with four clusters.
- **Cluster Analysis:** Visualized customer segments and compared their average income, spending, purchases, and recency.

## Dataset
Uses the iFood customer dataset (`ifood_df.csv`). Place the dataset in the project directory before running the script.

## Installation and Execution

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the script:

```bash
python customer_segmentation.py
```

## Future Enhancements
- Evaluate clusters using Silhouette Score.
- Build an interactive dashboard using Power BI or Streamlit.
- Develop targeted marketing strategies for each customer segment.


## Author
**Aditi Bhagat**

GitHub: [aditi-0926](https://github.com/aditi-0926)
