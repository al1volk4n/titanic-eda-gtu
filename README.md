# titanic-eda-gtu
# 🚢 Titanic EDA: Who Survived and Why?

An exploratory data analysis (EDA) of the classic Titanic dataset, focusing on survival patterns across demographic, socioeconomic, and age groups.

---

## 📌 Project Overview
This repository contains an end-to-end exploratory analysis developed as part of practical coursework and competitive portfolio building. The goal is to uncover the key factors that influenced passenger survival rates during the disaster.

- **Kaggle Notebook:** [View on Kaggle](https://www.kaggle.com/alivolkan1) *(Kaggle'daki notebook linkini buraya ekleyebilirsin)*
- **Dataset:** Titanic - Machine Learning from Disaster (Kaggle)

---

## 🔍 Key Findings & Benchmarks

1. **Overall Baseline:**
   - Out of 891 passengers, roughly **38.4%** survived, establishing a baseline benchmark where naive predictions achieve ~61.6% accuracy.
2. **Gender Disparity:**
   - Survival rate among female passengers was approximately **74%**, compared to only **19%** for male passengers, directly reflecting the maritime evacuation rule of *"women and children first"*.
3. **Socioeconomic Status (Pclass):**
   - **1st Class:** ~63% survival rate (easier access to boat decks).
   - **2nd Class:** ~47% survival rate.
   - **3rd Class:** ~24% survival rate (lower decks, significant barriers to evacuation).
4. **Age Dynamics:**
   - Children (ages 0–10) showed higher survival rates compared to young adults (ages 20–35), who constituted the largest casualty group.

---

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Kaggle Notebooks, Git & GitHub

---

## 📂 Project Structure
```text
├── README.md                              <- Project overview and insights
└── titanic-eda-who-survived-and-why.ipynb  <- Full analysis and code
