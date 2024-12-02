# 🎵 Maven Music Customer Churn Analysis 🎵

Welcome to the **Maven Music Customer Churn Analysis Project**! This repository contains all the materials needed for exploring, cleaning, and analyzing customer data, listening habits, and churn rates. Let's dive in! 🚀

---

## 🌟 **Project Overview**

Maven Music provided datasets about their customers, listening history, and sessions. This project aims to:

- 📊 Understand customer behavior and listening patterns.
- ❓ Investigate why customers churn.
- 🤖 Prepare a dataset for predictive modeling.

---

## 🗂 **Folder Structure**

Here's how the repository is organized:

```plaintext
📦 Maven Music Customer Churn Analysis
├── 📂 case_study      # Case study materials and documentation
├── 📂 data            # Raw data files (CSV and Excel)
├── 📂 Images          # Visualizations and screenshots
└──
└──readme
└── 📄 customer_churn_project.ipynb  # Jupyter Notebook with code and analysis
```

---

## 🚀 **Getting Started**

### **1. Prerequisites**

Ensure you have Python installed with the following libraries:

- 🐼 `pandas`
- 🧮 `numpy`
- 📊 `matplotlib`
- 🖼️ `seaborn`

### **2. How to Run the Code**

1. Clone this repository:
   ```bash
   git clone <repository_link>
   cd ds_mavens_music
   ```
2. Place the required data files into the `data/` folder.
3. Open the `customer_churn_project.ipynb` notebook.
4. Run all cells sequentially to replicate the analysis.

---

## 🔍 **Key Insights**

### 🎯 **Cancellation Insights**

- Customers with discounts have a **higher cancellation rate** (85.7%) compared to those without discounts.
- Customers with **fewer listening sessions** are more likely to cancel.

### 🎵 **Listening Behavior**

- **Pop music lovers** show higher churn rates.
- Podcasts listening has **no significant correlation** with cancellations.

---

## 📊 **Data Cleaning and Feature Engineering**

### 🧹 **Data Cleaning**

- Fixed typos in `Subscription Rate` (e.g., corrected $99.99 to $9.99).
- Standardized genres (e.g., combined `Pop` and `Pop Music`).
- Filled missing values for `Subscription Plan` with `Basic (Ads)`.

### 🛠 **Feature Engineering**

- 🧮 **Number of Sessions**: Unique sessions per customer.
- 🎵 **Percent Pop**: Percentage of Pop music listened.
- 🎙️ **Percent Podcasts**: Percentage of Comedy and True Crime podcasts.

---

## 📈 **Visualizations**

Check the 📂 `Images` folder for insightful visualizations like:

- Bar charts comparing cancellation rates for customers with/without discounts.
- Histograms showing the distribution of listening sessions.
- Pair plots exploring feature relationships.

---

## 🎉 **Results**

- Discounts are strongly correlated with cancellations.
- Engaged customers (more sessions) are less likely to churn.
- Genre preferences influence customer retention rates.

---

## 👨‍💻 **Contributors**

✨ **Taban Ngunar** ✨

---

## 📜 **License**

This project is licensed under the MIT License.
