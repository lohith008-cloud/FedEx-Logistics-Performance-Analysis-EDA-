# 🚚 FedEx Logistics Performance Analysis (EDA)

> A comprehensive Exploratory Data Analysis (EDA) project on the **SCMS Delivery History Dataset** to uncover shipment trends, freight cost drivers, vendor performance, and logistics insights using Python.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-blueviolet)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📖 Project Overview

Efficient logistics management is essential for minimizing transportation costs and ensuring timely deliveries. This project performs an in-depth Exploratory Data Analysis (EDA) on the **SCMS (Supply Chain Management System) Delivery History Dataset**, which contains over **10,000 shipment records**.

The objective is to identify operational patterns, understand the major factors influencing freight costs, analyze shipment performance, and generate actionable business insights for improving logistics efficiency.

---

## 🎯 Business Problem

Logistics organizations handle thousands of shipments across multiple countries, transportation modes, and vendors. Without proper analysis, it becomes difficult to:

- Identify the primary drivers of freight costs.
- Understand shipment distribution across countries.
- Compare shipment modes and delivery performance.
- Evaluate vendor efficiency.
- Improve operational planning and resource allocation.

This project addresses these challenges through comprehensive data exploration and visualization.

---

## 📂 Dataset Information

**Dataset:** SCMS Delivery History Dataset

### Dataset Summary

| Attribute | Value |
|-----------|--------|
| Rows | 10,324 |
| Columns | 33 |
| Format | CSV |
| Domain | Logistics & Supply Chain |

### Important Features

- Country
- Shipment Mode
- Vendor
- Fulfill Via
- Freight Cost (USD)
- Weight (Kilograms)
- Line Item Quantity
- Line Item Value
- Scheduled Delivery Date
- Delivered Date

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

### 🔹 Data Preprocessing

- Dataset loading
- Data inspection
- Data type conversion
- Missing value analysis
- Duplicate value checking
- Feature cleaning
- Data wrangling

---

### 🔹 Univariate Analysis

Performed analysis on:

- Shipment distribution by country
- Shipment mode frequency
- Freight cost distribution
- Line item quantity distribution
- Vendor order frequency

---

### 🔹 Bivariate Analysis

Relationship analysis between:

- Delivery delay vs Shipment Mode
- Shipment trend over time
- Freight Cost vs Weight
- Shipment Mode vs Freight Cost

---

### 🔹 Multivariate Analysis

Advanced analysis including:

- Freight Cost by Country, Shipment Mode & Vendor
- Line Item Value vs Freight Cost grouped by Vendor and Shipment Mode

---

## 📈 Key Business Insights

✔ Air shipments generally incur higher freight costs than other shipment modes.

✔ Shipment weight has a positive relationship with freight cost.

✔ Certain vendors consistently process a higher number of shipments.

✔ Shipment distribution varies significantly across countries.

✔ Transportation mode plays a major role in delivery performance and logistics cost.

✔ Data-driven shipment planning can significantly improve operational efficiency.

---

## 📁 Repository Structure

```
FedEx-Logistics-Performance-Analysis-EDA
│
├── fed_df.ipynb                    # Complete EDA Notebook
├── SCMS_Delivery_History_Dataset.csv
├── EDA_Fedex_Project.pptx          # Project Presentation
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/lohith008-cloud/FedEx-Logistics-Performance-Analysis-EDA-.git
```

### Navigate into the Project

```bash
cd FedEx-Logistics-Performance-Analysis-EDA-
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
fed_df.ipynb
```

---

## 📷 Visualizations Included

The project includes multiple visualizations such as:

- Count Plots
- Histograms
- Box Plots
- Scatter Plots
- Bar Charts
- Correlation Analysis
- Distribution Plots
- Multi-variable Comparisons

---

## 💼 Business Value

This analysis helps logistics organizations:

- Reduce transportation costs
- Optimize shipment planning
- Improve vendor selection
- Understand global shipment patterns
- Enhance supply chain efficiency
- Support strategic business decisions

---

## 📚 Future Improvements

- Build an interactive Power BI Dashboard
- Develop a Streamlit Web Application
- Predict Freight Cost using Machine Learning
- Detect delivery delays using predictive models
- Perform Time Series Forecasting
- Build Logistics KPI Dashboard

---

## 👨‍💻 Author

**Lohith Reddy**

📧 Email: lohithgayam007@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/lohith-reddy-gayam-14906a296

💻 GitHub: https://github.com/lohith008-cloud

---

Please consider giving this repository a ⭐ to support the project.
