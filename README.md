# 🛍️ Customer Segmentation using K-Means Clustering

This project applies **K-Means clustering** to segment mall customers based on their **Age**, **Annual Income**, and **Spending Score**.  
The goal is to help businesses better understand their customers and design **targeted marketing strategies** for each segment.

---

## 📂 Project Overview

Businesses often have diverse customers — some spend a lot, some very little, and others fall in between.  
Instead of treating all customers the same, **customer segmentation** helps divide them into groups (clusters) with similar purchasing behavior.  

In this project, we:
1. **Load and explore** mall customer data  
2. **Visualize patterns** in spending and income  
3. **Apply K-Means clustering** to group customers  
4. **Analyze cluster characteristics**  
5. **Visualize clusters in 2D and 3D**  

---

## 🧠 Key Learnings

- How to use **K-Means algorithm** for unsupervised learning  
- How to choose the **optimal number of clusters** using:
  - The **Elbow Method**
  - The **Silhouette Score**
- How to interpret and **visualize clusters**
- How to use **Pandas**, **Matplotlib**, **Seaborn**, and **Scikit-learn**

---

## 📊 Dataset Information

**File:** `Mall_Customers.csv`

| Column | Description |
|:-------|:-------------|
| CustomerID | Unique ID for each customer |
| Gender | Male or Female |
| Age | Age of the customer |
| Annual Income (k$) | Income in thousands |
| Spending Score (1-100) | Score assigned by the mall based on spending behavior |

---

## ⚙️ Technologies Used

- **Python 3**
- **Pandas** – for data manipulation  
- **NumPy** – for numerical operations  
- **Matplotlib** & **Seaborn** – for data visualization  
- **Scikit-learn** – for machine learning (K-Means, scaling, silhouette score)

---

## 🚀 Steps in the Project

### 1️⃣ Import Libraries and Load Data
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.cluster import KMeans
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import silhouette_score
