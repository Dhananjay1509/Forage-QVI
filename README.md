# 🏪 Quantium Data Analytics Virtual Experience Program – Forage

## 📌 Overview

This repository showcases my submission for the **Quantium Data Analytics Virtual Internship** on Forage. The program simulated real-world scenarios faced by Quantium's retail analytics team, with the primary objective being to analyze **supermarket chip purchases**, understand **customer segments**, and evaluate the **impact of experimental store layouts**.

Throughout this program, I applied industry-standard analytical methodologies and Python-based data science tools to uncover insights and support data-driven business decisions.

---

## 🧠 Tasks Summary

### 🔍 **Task 1: Data Preparation and Customer Analytics**
**Files**: `QVI_task1.ipynb`  
**Datasets**: `QVI_purchase_behaviour.csv`, `QVI_transaction_data.xlsx`

#### ✅ Key Highlights:
- Cleaned and transformed raw data:
  - Converted date from integer to datetime format.
  - Removed non-chip items and statistical outliers.
- Engineered new features such as brand and pack size.
- Analyzed customer behavior using:
  - **LIFESTAGE**: Describes household and family structure.
  - **PREMIUM_CUSTOMER**: Indicates price sensitivity and product preferences.
- Explored preferences of the high-value **Mainstream Young Singles/Couples** segment.

#### 📈 Insights:
- Top contributing segments by total chip sales:
  1. Budget Older Families
  2. Mainstream Young Singles/Couples
  3. Mainstream Retirees
- **Older Families** purchase the most chips on average.
- **Mainstream Young Singles/Couples**:
  - 28% more likely to buy Tyrells chips.
  - 32% more likely to buy large (270g) Twisties packets.
- Kettle chips and 175g packs are customer favorites across most groups.

---

### 🧪 **Task 2: Experimentation and Uplift Testing**
**Files**: `QVI_task2.ipynb`  
**Dataset**: `QVI_data.csv`

#### ✅ Objective:
Assess the impact of a new **store layout trial** conducted in three stores (77, 86, 88) during Feb–Apr 2019.

#### 📊 Methodology:
- Selected matched **control stores** based on:
  - Pearson correlation of pre-trial sales trends.
  - Magnitude distance (sales and customer count).
- Conducted **hypothesis testing** to measure significant uplift during trial months.

#### 📈 Insights:
- **Trial-Control Pairs**:
  - Store 77 ↔️ Store 233
  - Store 86 ↔️ Store 155
  - Store 88 ↔️ Store 40
- **Significant Improvements**:
  - Store 77 showed statistically significant uplift in **sales** (March, April) and **customer count** (February–April).
  - Store 86 showed uplift in **March**.
  - Store 88 did **not** show any statistically significant change.

---

### 📊 **Task 3: Commercial Application of Insights**
- Compiled a **presentation using the Pyramid Principle** to deliver:
  - Strategic recommendations to stakeholders.
  - Data-backed rationale for decision-making.
- Presented compelling visualizations and insights from Tasks 1 & 2.

---

## ⚙️ Dependencies

- **Language**: Python 3.8
- **Packages**:
  - `pandas`
  - `matplotlib`
  - `mlxtend`
  - `datetime`
  - `scikit-learn`
  - `scipy`

---

## 💡 Final Takeaway

This virtual experience honed my skills in:
- Exploratory data analysis (EDA)
- Customer segmentation
- Experiment design and statistical testing
- Data storytelling and stakeholder communication

I delivered actionable, commercially viable recommendations that aligned with business strategy — just like a real analyst at Quantium would.

---
