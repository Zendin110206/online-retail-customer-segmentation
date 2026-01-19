# Customer Segmentation Analysis: Online Retail I

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20Scikit--Learn%20%7C%20Seaborn-orange)
![Type](https://img.shields.io/badge/Type-Guided%20Learning%20Project-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project focuses on analyzing the **Online Retail I dataset** to perform **Customer Segmentation** using the **RFM (Recency, Frequency, Monetary)** framework and **K-Means Clustering**.

The main goal of this repository is to document my journey in understanding the **end-to-end Data Science workflow**: from cleaning messy real-world retail data to deriving actionable business insights for marketing strategies.

## 💾 Dataset

The dataset used in this analysis is the **Online Retail I** dataset.

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
- **Description:** Contains all transactions occurring for a UK-based and registered non-store online retail between 01/12/2009 and 09/12/2011.
- **Availability:** The dataset file (`online_retail_II.xlsx`) is **included** in the `data/` folder of this repository for ease of reproduction.

## 📚 Learning Resource & Attribution

This project is a **code-along implementation** based on the comprehensive tutorial by **TrentDoesMath**:
[Hands On Data Science Project: Understand Customers with KMeans Clustering](https://www.youtube.com/watch?v=afPJeQuVeuY).

> **Note:** I executed the code manually (no copy-paste) to ensure a deep understanding of every logical step, adding my own detailed comments, business interpretations, and validation steps.

## 🎯 Key Learnings & Outcomes

Through this project, I have successfully implemented:

1.  **Data Quality Assurance:** Handling real-world data anomalies (cancellations, bad debts, and non-product codes like `POST` or `M`).
2.  **Strategic Outlier Handling:** Instead of deleting high-value outliers (VIPs), I separated them into specific "Manual Clusters" to ensure they receive personalized treatment while keeping the K-Means model stable.
3.  **Feature Engineering (RFM):** Transforming raw transaction logs into meaningful customer metrics.
4.  **Hybrid Segmentation Strategy:** Combining **K-Means Clustering (4 Segments)** for the general population with **Rule-Based Grouping (3 Segments)** for outliers.

## 📊 Business Insights (6-Segment Strategy)

The final analysis identified 6 distinct customer profiles:

| Segment                   | Strategy                | Description                                                                    |
| :------------------------ | :---------------------- | :----------------------------------------------------------------------------- |
| **DELIGHT (VIP)**         | **Personal Assistance** | High spenders & frequent buyers. The top 1% most valuable customers.           |
| **PAMPER (Big Spenders)** | **Upselling**           | High monetary value but lower frequency. Needs incentives to visit more often. |
| **UPSELL (Wholesalers)**  | **B2B Partnership**     | Frequent buyers with lower basket size. Likely resellers/small businesses.     |
| **REWARD (Champions)**    | **Loyalty Program**     | The best of the general population. Active and loyal.                          |
| **RETAIN (Potential)**    | **Cross-Selling**       | Above-average customers who have potential to become Champions.                |
| **NURTURE (Newbies)**     | **Onboarding**          | New customers with low spend/frequency. Needs trust-building.                  |
| **RE-ENGAGE (Lost)**      | **Win-Back Campaign**   | Dormant customers who haven't purchased in a long time.                        |

## 🛠️ Tech Stack

- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn` (KMeans, StandardScaler, Silhouette Score)
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

_Implementation by [Muhammad Zaenal Abidin Abdurrahman](https://www.linkedin.com/in/zendin1102/) - 2026_
