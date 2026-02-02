# Market_A-B_Testing
# 📊 A/B Testing – Marketing Campaign Analysis

## 🎯 Objective
The objective of this project is to evaluate whether a new **Ad campaign** performs better than the existing **PSA campaign** in terms of user conversion rate using A/B testing and hypothesis testing in Python.

---

## 📁 Dataset
- **Source:** Marketing A/B Testing Dataset  
- **Total Users:** ~588,000  
- **Key Columns:**
  - `test group` → Experiment group (`psa` = control, `ad` = test)
  - `converted` → Conversion outcome (0 = No, 1 = Yes)

---

## 🧪 Methodology
1. Loaded and cleaned the dataset (removed unused index column).
2. Converted boolean conversion values into numeric format.
3. Split data into **Control (PSA)** and **Test (Ad)** groups.
4. Defined hypotheses:
   - **H0:** No difference in conversion rates between PSA and Ad.
   - **H1:** Conversion rates differ between PSA and Ad.
5. Applied a **two-sample t-test** to compare conversion rates.
6. Calculated p-value and 95% confidence interval.
7. Visualized conversion rate comparison.
8. Summarized results and provided a business recommendation.

---

## 📈 Results
- **PSA Conversion Rate:** ~1.78%
- **Ad Conversion Rate:** ~2.55%
- **p-value:** 1.7e-13
- **Confidence Interval:** Does not include zero

The extremely low p-value indicates a **statistically significant difference** between the two groups.

---

## ✅ Conclusion & Recommendation
The Ad campaign demonstrates a **statistically and practically significant improvement** in conversion rate compared to the PSA campaign.  
Based on the analysis, it is recommended to **roll out the Ad campaign** to improve overall conversions 🚀.

---

## 🗂 Files in This Repository
- `task11_abtest.ipynb` → Complete analysis and Python code
- `marketing_AB.csv` → Dataset used for analysis
- `ab_test_summary.csv` → Conversion rate and sample size summary
- `final_recommendation.txt` → Business recommendation
- `README.md` → Project overview

---

## 🛠 Tools & Libraries
- Python
- pandas
- numpy
- scipy
- matplotlib
- Google Colab

---

## 🧠 Key Learning Outcome
This project showcases the ability to apply **A/B testing and hypothesis testing** to make **data-driven product and marketing decisions** 📌.
