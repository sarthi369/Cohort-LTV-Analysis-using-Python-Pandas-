# 📊 Cohort & LTV Analysis (Python)

## 📌 Problem Statement

Analyze user behavior and revenue generation over time using cohort analysis and Lifetime Value (LTV) to understand retention patterns and monetization efficiency.

---

## 🧠 Approach

### 1. Cohort Creation

* Users grouped by signup month (`cohort_month`)

### 2. Time Indexing

* Calculated `cohort_index` as difference between transaction month and signup month

### 3. Revenue Aggregation

* Summed revenue for each cohort over time

### 4. Data Structuring

* Pivoted data into cohort vs time matrix
* Handled missing months using `reindex`

### 5. LTV Calculation

* Normalized revenue by cohort size to get average revenue per user

---

## 🛠 Tools Used

* Python
* Pandas

---

## 📊 Key Insights

* Some cohorts show **delayed monetization**, where users pay after initial months
* Certain cohorts generate **high initial revenue but fail to retain users**
* Strong cohorts exhibit **increasing LTV over time**, indicating better product engagement

---

## 🚀 Key Learnings

* Difference between **Retention vs LTV**
* Importance of **normalization (per user metrics)**
* Handling **missing data vs zero values**
* Real-world data challenges like **multiple transactions and delayed behavior**

---

## 📁 Project Structure

* Data creation (simulated datasets)
* Cohort analysis
* LTV calculation
* Business insights

---

## 📌 Conclusion

Cohort-based LTV analysis helps identify high-value user segments and provides actionable insights for improving retention, monetization, and overall product strategy.
