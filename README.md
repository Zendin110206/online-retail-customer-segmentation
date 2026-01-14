# Customer Segmentation Analysis: Online Retail II

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20Scikit--Learn%20%7C%20Seaborn-orange)
![Type](https://img.shields.io/badge/Type-Guided%20Learning%20Project-green)

## 📌 Project Overview
This project focuses on analyzing the **Online Retail II dataset** to perform **Customer Segmentation** using the **RFM (Recency, Frequency, Monetary)** framework and **K-Means Clustering**.

The main goal of this repository is to document my journey in understanding the **end-to-end Data Science workflow**: from cleaning messy real-world retail data to deriving actionable business insights for marketing strategies.

## 💾 Dataset
The dataset used in this analysis is the **Online Retail II** dataset.
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
- **Description:** Contains all transactions occurring for a UK-based and registered non-store online retail between 01/12/2009 and 09/12/2011.
- **Availability:** The dataset file (`online_retail_II.xlsx`) is **included** in the `data/` folder of this repository for ease of reproduction.

## 📚 Learning Resource & Attribution
This project is a **code-along implementation** based on the comprehensive tutorial by **TrentDoesMath**: 
[Hands On Data Science Project: Understand Customers with KMeans Clustering](https://www.youtube.com/watch?v=afPJeQuVeuY).

> **Note:** I am manually writing and executing the code (no copy-paste) to ensure a deep understanding of every logical step, while adding my own detailed comments and questions to explore the "Why" behind the "How".

## 🎯 Learning Objectives
By following this project, I aim to master the following concepts (Will be continuously updated as I learn):
1.  **Data Quality Assurance:** Learning how to verify data against documentation and identifying anomalies.
2.  **Strategic Data Cleaning:** Understanding *why* certain data points (like shipping costs or bad debts) must be excluded to avoid biasing the Customer Segmentation model.
3.  **Feature Engineering (RFM):** Transforming raw transaction logs into meaningful customer metrics (Recency, Frequency, Monetary).
4.  **Unsupervised Learning:** Implementing K-Means Clustering and interpreting the results for business strategy.

## 🛠️ Tech Stack
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`
- **Environment:** Jupyter Notebook

## 📂 Project Structure
```
├── data/
│   └── # online_retail_II.xlsx # Dataset file
│
├── notebooks/
│   └── online-retail-clustering.ipynb
│       # Jupyter Notebook containing the analysis
│
├── requirements.txt
│   # Python dependencies
│
└── README.md
    # Project documentation
```

---
*Implementation by [Muhammad Zaenal Abidin Abdurrahman](https://www.linkedin.com/in/zendin1102/) - 2026*