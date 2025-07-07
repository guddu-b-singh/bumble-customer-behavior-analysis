# bumble-customer-behavior-analysis
Exploratory data analysis of Bumble user profiles to uncover behavioral insights, lifestyle patterns, and data-driven recommendations using Python.



# 🧠 Customer Behavior Analysis on Bumble Using Python

This project presents an end-to-end exploratory data analysis (EDA) of user profile data from Bumble, a leading dating platform. Conducted as part of a Data Analyst milestone project with NextLeap, this analysis uncovers user behavior, demographic trends, lifestyle preferences, and provides actionable recommendations to improve matchmaking, engagement, and personalization strategies.

---

## 📌 Project Objectives

- Understand user demographics, habits, and behavior patterns.
- Analyze lifestyle and financial factors influencing engagement.
- Identify trends across regions, genders, and age groups.
- Support marketing and product decisions using data-driven insights.

---

## 🧹 Data Cleaning & Processing

- Removed duplicates & handled missing values.
- Converted `last_online` to datetime; replaced invalid income.
- Converted height from inches to centimeters.
- Grouped `age` and `income` into custom bins.
- Extracted `city`, `state`, `primary_language`, and `zodiac_importance`.
- Created `profile_completeness` and `last_active_days`.

---

## 📈 Key Analyses

### 📌 Univariate & Multivariate Insights:
- Most users are aged 18–35; majority are single and speak English.
- Gender imbalance observed, with higher male user count.
- Low to medium income users dominate the platform.
- Social drinking is popular among younger users (18–25).

### 🔗 Advanced Correlations:
- **Age vs. Income**: Slight positive correlation.
- **Height vs. Body Type**: Athletic users tend to be taller.
- **Drinks vs. Diet**: Most diet types correlate with social drinking.
- **Zodiac vs. Relationship Status**: Interesting patterns among signs.

---

## 🌍 Regional Insights

- Top cities: New York, Los Angeles, San Francisco
- Regional differences in income and age patterns
- English, Spanish, and French are top languages

---

## 🎯 Actionable Recommendations

- Introduce lifestyle-based matchmaking filters (e.g., diet, drinks, zodiac).
- Offer multi-language support to engage non-English users.
- Use income segments for premium pricing strategies.
- Address gender imbalance via targeted campaigns.
- Localized engagement in high-traffic regions like California & New York.

---

## 🛠️ Tools Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **PDF Report** for final presentation


