
# 🛍️ Mall Customers Clustering Analysis

This project applies **clustering techniques** to a dataset of mall customers, aiming to segment customers based on key attributes such as **Annual Income** and **Spending Score**. It uses unsupervised machine learning to identify customer groups that exhibit similar behaviors, which can help in targeted marketing strategies.

---

## 📁 Dataset

The dataset used is `Mall_Customers.csv`, which includes the following columns:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

---

## 🔧 Libraries Used

- `numpy` – numerical computations  
- `pandas` – data manipulation  
- `matplotlib` & `seaborn` – data visualization  
- `dabl` – quick data exploration  

---

## 🧪 Project Workflow

1. **Data Loading & Exploration**
   - Initial inspection (shape, head, tail, random samples)
2. **Preprocessing**
   - Data cleaning, null value handling (if any)
   - Data type conversions and basic statistics
3. **Data Visualization**
   - Distribution plots, boxplots, pairplots, and heatmaps
4. **Clustering Analysis**
   - Applying **K-Means Clustering**
   - Determining optimal number of clusters using the **Elbow Method**
   - Visualizing the customer segments in 2D
5. **Interpretation**
   - Analyzing cluster patterns and business insights

---

## 🎯 Objective

Segment mall customers based on demographics and shopping behaviors to:
- Improve targeted marketing
- Personalize promotions
- Understand customer profiles

---

## 🚀 Future Enhancements

- Include behavioral and transactional data  
- Try other clustering algorithms (e.g., DBSCAN, Hierarchical)  
- Deploy the model with a web interface using Flask or Streamlit  

---

## 👤 Author

Created by **Ahmed SHERIF**  
GitHub: github.com/cesar6643

Feel free to explore, fork, or suggest improvements 😊

---
