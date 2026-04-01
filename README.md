# 🛍 Customer Segmentation using K-Means & Hierarchical Clustering

## 📌 Project Overview

This project applies **unsupervised machine learning techniques** to segment customers into meaningful groups based on their behavior.

Using clustering algorithms, we uncover hidden patterns in customer data to support **data-driven business decisions** such as targeted marketing, customer retention, and revenue optimization.

---

## ❗ Problem Statement

Businesses often struggle to understand their customers due to a lack of segmentation. Without clear insights:

* Marketing campaigns become inefficient
* High-value customers are not prioritized
* Revenue opportunities are missed

This project addresses these challenges by grouping customers into distinct segments using machine learning.

---

## 🎯 Objectives

* Perform exploratory data analysis (EDA)
* Apply clustering techniques to segment customers
* Identify optimal number of clusters
* Compare K-Means and Hierarchical clustering
* Generate actionable business insights

---

## 📂 Dataset

This project uses the **Mall Customer Segmentation Dataset**, which includes:

* Customer ID
* Gender
* Age
* Annual Income
* Spending Score

📥 Source: Kaggle (Customer Segmentation Dataset)

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Data cleaning and formatting
* Feature selection
* Feature scaling using StandardScaler

### 2. Exploratory Data Analysis (EDA)

* Distribution analysis
* Correlation analysis
* Customer behavior patterns

### 3. K-Means Clustering

* Elbow Method to determine optimal clusters
* Model training and cluster assignment
* Visualization of customer segments

### 4. Hierarchical Clustering

* Dendrogram analysis
* Cluster extraction
* Validation of K-Means results

---

## 📊 Results & Insights

### 🔹 Key Findings:

* Identified **5 distinct customer segments**
* High-income & high-spending customers are the most valuable
* Low-income segments require cost-sensitive strategies
* Medium segments benefit from retention campaigns

---

## 🧠 Business Insights

| Customer Segment  | Characteristics            | Strategy                     |
| ----------------- | -------------------------- | ---------------------------- |
| High Value        | High income, high spending | VIP programs, premium offers |
| Potential Growth  | High income, low spending  | Upselling campaigns          |
| Budget Customers  | Low income, high spending  | Loyalty programs             |
| Low Value         | Low income, low spending   | Cost-efficient marketing     |
| Average Customers | Balanced behavior          | Retention strategies         |

---

## 🛠 Tools & Technologies

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* SciPy
* Google Colab / Jupyter Notebook

---

## 📂 Project Structure

```
customer-segmentation/
│
├── data/
│   └── Mall_Customers.csv
│
├── notebooks/
│   └── K_Means_&_Hierarchical_Clustering.ipynb
│
├── images/
│   └── plots.png
│
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/yourusername/customer-segmentation.git
```

2. Navigate to the project folder:

```
cd customer-segmentation
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run the notebook:

```
jupyter notebook
```

---

## ⚖️ K-Means vs Hierarchical Clustering

| Feature     | K-Means    | Hierarchical |
| ----------- | ---------- | ------------ |
| Speed       | Fast       | Slow         |
| Scalability | High       | Low          |
| Use Case    | Production | Analysis     |
| Output      | Clusters   | Dendrogram   |

---

## 🚀 Conclusion

This project demonstrates how clustering techniques can:

* Reveal hidden customer patterns
* Improve marketing strategies
* Enable data-driven business decisions

Combining **K-Means (for scalability)** and **Hierarchical Clustering (for interpretability)** provides a powerful approach to customer segmentation.

---

## 🔮 Future Improvements

* Add DBSCAN clustering
* Build an interactive dashboard (Streamlit/Power BI)
* Deploy as a web application
* Integrate real-time customer data

---

## 💼 Portfolio Highlights

✔ End-to-end machine learning workflow
✔ Real-world dataset
✔ Business-driven insights
✔ Clean and professional code

---

## 📬 Contact

If you'd like to collaborate or have questions:

* LinkedIn: *[www.linkedin.com/in/muradamin]*
* Email: *[muradamen10@gmail.com]*

---

⭐ If you found this project useful, feel free to star the repository!

