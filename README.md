## 📦 Supply Chain Analysis & Late Delivery Prediction

### 🚀 Project Overview

This project analyzes delivery performance for a global e-commerce company to identify **root causes of late deliveries**, quantify **business impact**, and build a **predictive model** to flag high-risk orders.

The analysis is based on **172,765 orders** across multiple regions and operational dimensions.

---

## 🎯 Business Problem

A global e-commerce company is experiencing:

* High **late delivery rates**
* Reduced **customer trust**
* Significant **profitability loss**

Actual shipping times frequently deviate from promised timelines, making delivery performance unreliable.

---

## 📊 Key Insights

* 📉 **54.71%** of orders are delivered late
* 💰 **$2.1M profit at risk** due to delays
* 📦 Total orders analyzed: **172,765**
* 💵 Total profit: **$7.5M**
* ⏱️ 90% of delays are within **3 days**
* 🤖 Predictive model accuracy: **~74%**

---

## 🔍 Analysis Performed

### 1. Exploratory Data Analysis (EDA)

* Delay trends across **month, day, and hour**
* Distribution of **delay days**
* Profit vs delay relationship

### 2. Profitability Analysis

* 80% orders profitable
* ~19% loss-making → heavily linked to delays

### 3. Bottleneck Detection

Analyzed delay % across:

* Shipping Mode
* Region
* Customer Segment
* Department
* Order Status
* Payment Type

### 🚨 Key Finding:

* **Shipping Mode is the biggest issue**

  * First Class → ~100% delay
  * Second Class → ~80%
  * Standard → ~40%

---

## 🧠 Root Cause Analysis

Deep dive into high-delay region (Central Africa):

Top drivers:

* Shipping Mode inefficiency
* Payment delays (Pending / Review)
* High-delay product categories (Outdoors, Golf)

👉 Conclusion:
This is a **system-wide operational issue**, not region-specific.

---

## 🤖 Machine Learning Model

Model Used: **Random Forest Classifier**

### Performance:

* Accuracy: ~66–74%
* Balanced precision & recall

### Purpose:

Predict whether an order will be delayed **before shipping**, enabling proactive action.

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

## 📈 Strategic Recommendations

### 🔴 Critical

* Audit First & Second Class shipping immediately

### 🟠 High Priority

* Deploy predictive alert system
* Fix payment processing delays

### 🟡 Medium

* Plan for seasonal demand spikes
* Default to Standard Shipping where possible
* Audit high-delay departments

### 🔵 Low

* Reduce loss-making orders
* Continuously retrain ML model

---

## 📂 Project Structure

```
SupplyChain_Analysis/
│
├── notebook.ipynb        # Full analysis & modeling
├── README.md             # Project documentation
├── report.pdf            # Final business report
└── dataset.csv           # Dataset (if included)
```

---

## 💡 Business Impact

* Identified **systemic inefficiencies** affecting >50% of orders
* Highlighted **$2.1M revenue risk**
* Built a **deployable ML solution** for proactive delay detection
* Provided **clear operational strategies** for improvement

---

## 🔗 Future Improvements

* Add real-time prediction API
* Include external features (weather, logistics load)
* Improve recall to >80%
* Build dashboard (Power BI / Streamlit)

---

## 👤 Author

**Dev Prince**
(Data Analyst)

---

