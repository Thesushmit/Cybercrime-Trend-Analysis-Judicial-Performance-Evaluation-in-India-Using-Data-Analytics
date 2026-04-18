# 🚀 Cybercrime-Trend-Analysis-Judicial-Performance-Evaluation-in-India-Using-Data-Analytics

## 📌 Project Overview

This project analyzes the **increasing trend of cybercrime in India** and evaluates how effectively the **judicial system is responding** to these crimes.

It combines:

* 📊 Cybercrime data (2021–2023)
* ⚖️ Judicial case data (conviction, pendency, etc.)

The project applies a complete **data science pipeline**:

> Descriptive Analysis → EDA → Predictive Modeling → Inferential Analysis → Prescriptive Insights

---

## 🎯 Objectives

* Analyze **growth of cybercrime over time**
* Compare **state-wise crime distribution**
* Evaluate **judicial efficiency (conviction & pendency)**
* Predict **future cybercrime trends**
* Provide **data-driven recommendations**

---

## 📂 Datasets Used

### Dataset 1: Cybercrime Data

* Year-wise cases (2021, 2022, 2023)
* State/UT
* Population
* Crime rate
* Chargesheeting rate

### Dataset 2: Judicial Data

* Pending cases
* Convictions
* Acquittals
* Pendency %
* Conviction rate

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas (Data Processing)
* NumPy
* Matplotlib & Seaborn (Visualization)
* Scikit-learn (Machine Learning)
* Plotly (Dashboard)

---

## 📊 Analysis Performed

### 1. Descriptive Analysis

* Total cybercrime cases (year-wise)
* Top states with highest crime
* Average crime rate
* Judicial statistics summary

---

### 2. Exploratory Data Analysis (EDA)

* 📈 Trend analysis (2021–2023)
* 📊 State-wise comparison
* 🔍 Population vs Crime relationship
* ⚖️ Conviction rate & Pendency analysis
* 🔥 Correlation heatmap

---

### 3. Predictive Analysis (Machine Learning)

The following models were used:

| Model                   | Purpose                   |
| ----------------------- | ------------------------- |
| Linear Regression       | Basic trend prediction    |
| Polynomial Regression   | Capture non-linear growth |
| Random Forest Regressor | Handle complex patterns   |

👉 Prediction:

* Forecast cybercrime cases for **2024**

---

### 4. Judicial Performance Analysis

* State-wise conviction rate comparison
* Pendency percentage analysis
* Identification of:

  * Best performing states
  * Worst performing states

---

### 5. Inferential Analysis

* Correlation between:

  * Cybercrime vs Pendency %
  * Cybercrime vs Conviction Rate

👉 Insight:

* High cybercrime often correlates with higher case backlog

---

### 6. Prescriptive Analysis

Recommendations include:

* Fast-track cybercrime courts
* Improved digital forensics
* Awareness programs
* Stronger inter-state coordination
* Judicial capacity improvement

---

## 📈 Dashboard

An interactive dashboard is generated using Plotly including:

* Cybercrime trend visualization
* State-wise comparison
* Judicial performance metrics
* Prediction results

---

## ▶️ How to Run

### Step 1: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly
```

### Step 2: Update Dataset Paths

```python
cyber_df = pd.read_csv("dataset1.csv")
judicial_df = pd.read_csv("dataset2.csv")
```

### Step 3: Run Notebook / Script

* VS Code → Open `.ipynb`
* Run all cells

---

## ⚠️ Limitations

* Only **3 years of data** available
* Predictions are **approximate**
* Random Forest performance is limited due to small dataset

---

## 💡 Key Insights

* Cybercrime is **increasing rapidly**
* Some states show **high concentration of cases**
* Judicial system faces **high pendency**
* Conviction rates vary significantly

---

## 📌 Conclusion

The study reveals a growing gap between **cybercrime growth** and **judicial response capacity**, highlighting the need for:

* Faster legal processes
* Better cybersecurity infrastructure
* Increased awareness

---

## 👨‍💻 Authors

* **Shivansh Lohani**
  PRN: 23070521141

* **Shreyasi Gidmare**
  PRN: 23070521146

* **Sushmit Partakke**
  PRN: 23070521156
---
