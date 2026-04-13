# SmartCart Customer Clustering System

## 📌 Project Overview
SmartCart is an e-commerce platform seeking to transition from generic marketing to data-driven personalization. This project implements an **unsupervised machine learning** pipeline to segment 2,240 customers into distinct groups based on demographics, spending behavior, and engagement patterns.

By identifying these clusters, the business can optimize marketing spend, improve customer retention, and tailor promotions to specific high-value or churn-prone segments.

## 📊 Dataset Description
The dataset contains 22 attributes for each customer, categorized into:
- **Demographics:** Age, Education, Marital Status, Income, and Household composition.
- **Spending (Mnt):** Expenditure on Wines, Fruits, Meat, Fish, Sweets, and Gold.
- **Channels:** Number of purchases via Web, Catalog, Store, and Deals.
- **Engagement:** Monthly website visits and campaign responses.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab (GPU accelerated)

## 🚀 Key Features & Workflow
1. **Data Cleaning:** Handled missing income values and removed outliers to ensure robust clustering.
2. **Feature Engineering:** - Derived `Age` from birth years.
   - Calculated `Total_Spending` and `Total_Children` for better dimensionality.
   - Grouped categorical variables (Education & Marital Status) into simplified classes.
3. **Preprocessing:** Applied `StandardScaler` to normalize features, ensuring distance-based algorithms perform accurately.
4. **Clustering:** Implemented **K-Means Clustering** to segment the customer base.
5. **Analysis:** Detailed profiling of each cluster to define "Value Segments" (e.g., High-Spenders vs. Deal-Seekers).

## 📈 Results
The system successfully identified 4 distinct customer clusters:
- **Cluster 0 & 2:** Often represent moderate spenders with larger families.
- **Cluster 1 & 3:** Higher-income segments with significant spending in Meat and Wine categories and lower household sizes.

## 📂 Repository Structure
- `Smart_Cart.ipynb`: Complete Python implementation and data visualization.
- `SmartCart Clustering System.pdf`: Detailed project documentation and problem statement.
- `smartcart_customers.csv`: Dataset used for training (ensure this is uploaded or linked).

## 💡 How to Use
1. Clone the repository.
2. Install dependencies: `pip install pandas scikit-learn matplotlib seaborn`.
3. Run `Smart_Cart.ipynb` to view the analysis and cluster visualizations.

---
**Author:** Amrit Pratya  
**Course:** Apna College Prime AI/ML Batch
