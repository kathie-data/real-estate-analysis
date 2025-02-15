# 📊 Real Estate Price Prediction with Python

## 🔹 Overview

This project analyzes **real estate prices** using Python. We explore key pricing trends, apply **correlation analysis**, and build **predictive models** to understand the relationship between floor area and resale price.

## 🔹 Project Objectives

- 📌 Clean and preprocess real estate data
- 📌 Perform **Exploratory Data Analysis (EDA)**
- 📌 Identify **correlation** between floor area and price
- 📌 Develop **Linear Regression Model** to predict resale prices
- 📌 Provide **business insights** for real estate valuation

## 📂 Files Included

| File                              | Description                                           |
| --------------------------------- | ----------------------------------------------------- |
| `real_estate_analysis.py`         | Python script with full analysis & model building     |
| `Real_Estate_Analysis_Python.pdf` | Final PowerPoint presentation with insights & visuals |
| `README.md`                       | Project documentation (this file)                     |

## 🔹 Dataset Information

- 📌 **Source:** Real estate resale transactions
- 📌 **Total Records:** 1000
- 📌 **Key Features:**
  - **Floor\_Area\_Sqm**: Size of the property
  - **Resale\_Price**: Price of the property
  - **Town**: Location of the property
  - **Lease\_Commence\_Year**: Lease start year

## 🔹 Key Findings

- **Correlation:**
  - Floor area and resale price have a **weak positive correlation** (**0.0706**), meaning size alone is not a strong predictor.
- **Linear Regression Model:**
  - **Equation:** `Resale_Price = 443006.57 + 287.92 * Floor_Area_Sqm`
  - **Interpretation:** Each additional **1 sqm** increases the price by **\~\$288**.
- **Business Insight:** Location, market trends, and other economic factors have a **greater impact on resale prices** than floor area alone.

## 🔹 Model & Visualization

- **Exploratory Data Analysis (EDA):**
  - 📊 Scatter plot of `Floor_Area_Sqm` vs. `Resale_Price`
  - 📊 Histogram of resale price distribution
- **Regression Model:**
  - 🔴 **Red line** = Predicted price
  - 🔵 **Blue dots** = Actual resale prices
  - 📌 If points follow the red line, the model is accurate.

## 🚀 Future Improvements

- 🔹 **Enhance feature selection**: Include **mortgage rates, neighborhood ratings, and property type**.
- 🔹 **Apply advanced models**: Use **Random Forest, XGBoost**, or **Gradient Boosting** to improve accuracy.
- 🔹 **Expand data scope**: Incorporate additional **geographical and economic factors**.

## 🛠️ How to Run the Code

1️⃣ Clone this repository:

```bash
 git clone https://github.com/yourusername/real-estate-analysis.git
```

2️⃣ Navigate to the directory:

```bash
 cd real-estate-analysis
```

3️⃣ Install required libraries:

```bash
 pip install pandas numpy matplotlib seaborn scikit-learn
```

4️⃣ Run the Python script:

```bash
 python real_estate_analysis.py
```

## 📞 Contact

💡 **Author:** [Katherine Ponce]\
🔗 **LinkedIn:** [https://n9.cl/n6a8r]

---

📢 If you find this project helpful, feel free to ⭐ star the repository and share your feedback! 🚀

