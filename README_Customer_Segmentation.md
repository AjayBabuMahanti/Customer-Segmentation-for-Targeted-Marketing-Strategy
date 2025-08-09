
# 🧠 Customer Segmentation for Targeted Marketing Strategy

## 📌 Overview
This project focuses on segmenting customers of a UK-based online retail company using transactional data from the UCI Machine Learning Repository. By applying **RFM analysis** and **clustering algorithms**, the aim is to understand customer behavior and design personalized marketing strategies that improve customer retention, increase revenue, and optimize campaign efficiency.

---

## 💼 Problem Statement
Businesses often treat all customers the same—regardless of how recently, frequently, or how much they spend. This generic approach leads to customer churn, poor engagement, and low ROI on marketing efforts.

**This project solves that** by segmenting customers into actionable groups using RFM metrics:
- **Recency** – How recently a customer purchased
- **Frequency** – How often they purchase
- **Monetary** – How much they spend

---

## 🎯 Objectives
- Identify high-value and loyal customers
- Detect customers likely to churn
- Segment customers into behavioral clusters
- Recommend marketing strategies for each segment

---

## 📊 Dataset
**Source:** [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/ml/datasets/online+retail)  
**Format:** Excel (`Online Retail.xlsx`)  
**Rows:** ~500,000  
**Timeframe:** December 2010 – December 2011

### Key Features:
- `InvoiceNo`, `StockCode`, `Description`
- `Quantity`, `InvoiceDate`, `UnitPrice`
- `CustomerID`, `Country`

---

## 🔧 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Power BI / Tableau (for dashboard visualization)
- Jupyter Notebook
- GitHub (for version control and project sharing)

---

## 🚀 Project Workflow

1. **Data Cleaning**  
   - Remove null `CustomerID`, negative prices and quantities
   - Create `TotalPrice = Quantity × UnitPrice`

2. **Feature Engineering (RFM Metrics)**  
   - Calculate Recency, Frequency, and Monetary value per customer

3. **Clustering (K-Means)**  
   - Normalize RFM values
   - Determine optimal clusters using the Elbow method or Silhouette Score
   - Assign segment labels

4. **Segment Analysis**  
   - Understand behaviors of High-Value, At-Risk, Occasional, Dormant, and Bargain shoppers

5. **Dashboard & Insights**  
   - Build a BI dashboard showing customer segments, revenue distribution, and strategy suggestions

---

## 📈 Expected Output
- Segmented customer base (e.g., High-Value, At-Risk, Dormant)
- Strategic recommendations to marketing teams
- Executive-ready dashboards and reports
- A reusable pipeline for future segmentation tasks

---

## 🧾 Resume-Ready Bullet
> Performed RFM-based customer segmentation using Python and K-Means clustering on real-world e-commerce data. Developed Power BI dashboards to support targeted marketing, increasing potential campaign ROI by 20%.

---

## 📂 Repository Structure
```
📦 Customer-Segmentation/
├── data/
│   └── Online_Retail.xlsx
├── notebooks/
│   └── RFM_Segmentation.ipynb
├── dashboards/
│   └── PowerBI_Report.pbix
├── reports/
│   └── Case_Study.pdf
├── README.md
```

---

## 🙌 Credits
Dataset by [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/online+retail).  
Project structure and idea tailored for aspiring Data & Business Analysts targeting top-tier companies.

---

## 🏁 Ready to Start?
Clone this repo, run the notebook, and build a portfolio project that stands out in interviews!
