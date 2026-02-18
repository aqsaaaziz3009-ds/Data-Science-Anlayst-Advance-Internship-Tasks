
# 🛍️ Customer Segmentation Using Unsupervised Learning

##  Overview

This project focuses on segmenting customers based on their spending behavior and income patterns using unsupervised machine learning. The goal is to identify meaningful customer groups and design targeted marketing strategies for each segment.

---

##  Objective

* Perform Exploratory Data Analysis (EDA) on mall customer data
* Apply K-Means clustering to identify customer segments
* Use PCA and t-SNE for dimensionality reduction and visualization
* Interpret cluster behavior and generate business insights
* Suggest marketing strategies for each customer segment

---

## Dataset

**Mall Customers Dataset**

The dataset contains demographic and behavioral attributes of mall visitors.

### Features:

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

---

## Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* PCA & t-SNE (Dimensionality Reduction)

---

## Workflow

### 1️. Data Preprocessing

* Loaded dataset using pandas
* Selected relevant features (Income & Spending Score)
* Applied feature scaling using StandardScaler

---

### 2️.Exploratory Data Analysis (EDA)

* Gender distribution analysis
* Age distribution visualization
* Income vs Spending Score scatter plots
* Observed natural clustering patterns

---

### 3️. Finding Optimal Clusters

Used the **Elbow Method** to determine the optimal number of clusters.
The curve indicated an optimal value of **K = 5**.

---

### 4️. Model Building

Applied **K-Means Clustering** to segment customers into 5 distinct groups.

---

### 5️. Cluster Visualization

Two dimensionality reduction techniques were used:

* **PCA (Principal Component Analysis)**

  * Linear dimensionality reduction
  * Fast and interpretable visualization

* **t-SNE (t-Distributed Stochastic Neighbor Embedding)**

  * Non-linear dimensionality reduction
  * Produces more compact and visually separable clusters

---

## Results

* Successfully identified 5 meaningful customer segments
* Clear separation observed using PCA and t-SNE visualizations
* Distinct high-value and low-engagement customer groups discovered

---

## Business Insights & Strategies

###  High Income – High Spending

* Premium customers
* Strategy: VIP memberships, luxury promotions

###  High Income – Low Spending

* Untapped potential
* Strategy: Personalized offers and loyalty rewards

### Medium Income – Medium Spending

* Regular customers
* Strategy: Bundled deals and seasonal discounts

###  Low Income – High Spending

* Impulse buyers
* Strategy: Limited-time deals and flash sales

###  Low Income – Low Spending

* Budget-conscious customers
* Strategy: Affordable product lines and value offers

---

##  Key Learnings

* Hands-on experience with unsupervised learning
* K-Means clustering implementation
* Dimensionality reduction using PCA and t-SNE
* Translating data insights into business strategies

---

## Future Improvements

* Use more features for deeper segmentation
* Apply hierarchical clustering
* Try DBSCAN for density-based clustering
* Build real-time recommendation systems

---

## 📎 Project Structure

```
├── Task2.ipynb
├── README.md
└── dataset/
```

---

## 🙌 Author

**Aqsa Aziz**
Data Science Intern
