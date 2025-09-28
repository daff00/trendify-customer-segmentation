# Trendify E-commerce Sales Analysis & Customer Segmentation

## 📖 Project Overview

This project performs an in-depth analysis of a UK-based online retailer's sales data from 2009 to 2011. The primary goals are to uncover sales patterns, identify top-performing products and key customer demographics, and segment customers based on their purchasing behavior using RFM analysis and K-Means clustering. The final output provides actionable recommendations to enhance marketing strategies and drive business growth.

---

## 🎯 Business Problem

A UK-based online retailer, "Trendify," wants to leverage its transactional data to make more informed, data-driven decisions. The management team is seeking answers to the following key questions:
1. What are the overall sales trends on a monthly and quarterly basis?
2. Which are the top 10 best-selling products by revenue and quantity?
3. Who are the top 10 most valuable customers?
4. What is the geographical distribution of sales?
5. How can we segment our customers based on their purchasing behavior?

---

## 💾 Dataset

The analysis is based on the **"Online Retail"** dataset from the UCI Machine Learning Repository. This is a transnational dataset that contains all the transactions occurring between 01/12/2009 and 09/12/2011 for a UK-based online retail company.

-   **Source:** [UCI Machine Learning Repository](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
-   **Attributes:** `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`.

---

## 🛠️ Tech Stack

-   **Programming Language:** Python 3.12
-   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, Yellowbrick

---

## 📊 Analysis Workflow

1.  **Data Cleaning & Preprocessing:** Handled missing values, removed duplicates, corrected data types, and filtered out returns (negative quantities).
2.  **Exploratory Data Analysis (EDA):** Investigated sales trends over time, identified top-selling products by revenue and quantity, and analyzed the geographical distribution of sales.
3.  **RFM Analysis:** Calculated Recency, Frequency, and Monetary values for each customer to quantify their purchasing behavior.
4.  **K-Means Clustering:** Used the Elbow method to determine the optimal number of clusters (k=4) and segmented customers into distinct groups based on their scaled RFM metrics.
5.  **Visualization & Recommendation:** Visualized the resulting clusters and derived actionable business recommendations for each segment.

---

## 📈 Key Findings & Visualizations

### 1. Sales Trend Analysis
Sales show a significant upward trend, peaking sharply in November of each year, likely due to holiday season shopping.

`![Sales Trend](/sales-analysis/reports/figures/sales_trend.png)`

### 2. Top Performing Products by Sales
The analysis identified a core set of products that are major driver of sales, with "REGENCY CAKESTAND 3 TIER" being the clear leader on top.

`![Top Products by Sales](./reports/figures/top_sales.png)`

### 3. Top Performing Products by Quantity
The analysis identified a core set of products that are major drivers of sales quantity, with "World War 2 Gliders Asstd Designs" being the clear leader of top sales quantity.

`![Top Products by Quantity](./reports/figures/top_volume.png)`

### 4. Customer's Origin
Most of customers are based on UK.

`![Customer Origin](./reports/figures/cusotomer_origins.png)`

### 5. Customer Segmentation with K-Means
Four distinct customer segments were identified, each with unique purchasing characteristics. The 3D plot below visualizes these clusters based on their RFM values.

`![Customer Segments](./reports/figures/rfm_3d_cluster.png)`


---

## 💡 Actionable Business Recommendations

Based on the analysis, the following actions are recommended to optimize marketing and sales strategies:

1. **Re-engage At-Risk Customers** <br>
Analysis revealed a large"At-Risk" customersegment. Action: Launch atargeted email campaignwith a special discount towin back these customersand prevent churn.

2. **Retain High-Value Customers**<br>
An elite group of "VIP" &"Champion" customers(<1%) generates a massiveshare of revenue. Action:Implement an exclusiveloyalty program withspecial perks to ensureretention of these criticalcustomers.

3. **Optimize Product Strategy**<br>
Analysis identified distinctproduct groups (high-value vs. high-volume).Action: Promote high-valueitems to VIPs and usepopular, low-cost items as"add-ons" to increaseaverage order value.

4. **Drive Strategic Expansion**<br>
Geographical analysisshows Australia is the top-performing non-Europeanmarket. Action: Launchtargeted digital advertisingfor Australia to accelerategrowth and capitalize onthis proven product-market fit.

---

## ⚙️ Setup and Installation

To run this analysis yourself, please follow these steps:

1.  Clone the repository:
    ```bash
    git clone [https://github.com/daff00/trendify-customer-segmentation](https://github.com/daff00/trendify-customer-segmentation)
    ```
2.  Create and activate a Python virtual environment. This project was developed using **Python 3.12.10**.
    ```bash
    # Create the environment
    python -m venv venv
    # Activate it (Windows)
    .\venv\Scripts\activate
    ```
3.  Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4.  You can now run the Jupyter Notebook located in the `/notebooks` directory.

---

## 📬 Contact

-   **Daffa Kaisha Pratama Chandra** - [daffakpc21@gmail.com](mailto:daffakpc21@gmail.com)
-   **LinkedIn:** [https://www.linkedin.com/in/daffakaisha/](https://www.linkedin.com/in/daffakaisha/)
-   **Project Link:** [https://github.com/daff00/trendify-customer-segmentation](https://github.com/daff00/trendify-customer-segmentation)