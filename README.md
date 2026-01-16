# 🧠 Depression Data Analysis Dashboard (Tableau)

<p align="center">
  <img src="images/dashboard.png" alt="Depression Tableau Dashboard Preview" width="900">
</p>

This project presents an interactive **Tableau dashboard** that explores
potential influencing factors of **depression** through multi-dimensional data analysis.

Depression is a **complex mental health issue** influenced by a combination of
demographic, health-related, social, and lifestyle factors.
This dashboard aims to answer the core question:

> **Why do people suffer from depression?**

---

## 📌 Project Overview

Using depression-related population data, this project analyzes depression cases
from **five major perspectives**, each represented by a dedicated visualization:

1. Age Groups  
2. Health History  
3. Family Environment  
4. Social Environment  
5. Lifestyle Factors  

The goal is to provide a **data-driven overview** of how different factors are
associated with depression, rather than making medical diagnoses.

---

## 🧩 Dashboard Structure & Key Findings (5 Visualizations)

### 1️⃣ Age Groups and Depression

A line chart illustrates the number of depression cases across four age stages:
- Youth
- Early Adulthood
- Middle Adulthood
- Older Adulthood

**Key insights:**
- The number of depression cases increases with age.
- **Older Adulthood** shows the highest number of depression cases.
- **Youth** shows the lowest number.

This suggests a clear association between age stage and depression prevalence.

---

### 2️⃣ Health History and Depression

Health history is analyzed from four aspects:
- History of Substance Abuse
- History of Mental Illness
- Family History of Depression
- Chronic Medical Conditions

**Findings:**
- For each health factor, the number of depression cases *without* the condition
  is approximately **twice** that of cases *with* the condition.
- Further analysis shows that individuals labeled as **Health A (excellent health)**
  exhibit no issues across all four health dimensions.
- This group accounts for roughly **one quarter of the total population**.

**Conclusion:**
Poor health history significantly increases the risk of depression,
while good health may play a protective role.

---

### 3️⃣ Family Environment and Depression

Family environment is examined through:
- Marital Status
- Fertility Status (having children or not)

**Key observations:**
- Among individuals with depression, **more than half are married**,
  indicating that depression is not limited to single individuals.
- Among individuals without children, **single individuals represent the largest
  proportion** of depression cases.
- For marital statuses other than single (such as married, divorced, and widowed),
  **individuals without children consistently account for approximately one quarter
  of depression cases within each marital group**.

**Conclusion:**
Fertility status has a more direct association with depression,
while marital status plays a more indirect role.

---

### 4️⃣ Social Environment: Education, Income, and Employment Status

This section explores:
- Education Level
- Income Level
- Employment Status

**Findings:**
- Education and income show a positive correlation.
- Depression cases are not concentrated in either the highest or lowest income groups.
- Notably, the number of depression cases among **employed individuals is approximately
  twice that of unemployed individuals**.

**Conclusion:**
Employment status shows a strong association with depression,
while education and income exert indirect effects.

---

### 5️⃣ Lifestyle Factors and Depression

Lifestyle is analyzed across five dimensions:
- Alcohol
- Dietary Habits
- Physical Activity
- Sleep
- Smoking

**Key findings:**
- Depression cases exist under all lifestyle conditions.
- Individuals labeled as **Lifestyle A (excellent lifestyle)** perform well across
  all five dimensions.
- This group represents only **approximately 1 in 400** of the total population.

**Conclusion:**
Lifestyle has a significant impact on depression,
and healthier lifestyles may help reduce depression risk.

---

## 📊 Overall Insights

Combining all five dimensions, the analysis suggests that depression is closely related to:
- Health history
- Fertility status
- Employment status
- Lifestyle factors

Individuals with **good health**, **no children**, **no employment**, and a
**healthy lifestyle** show an extremely low observed depression risk,
approximately **1 in 20,000** of the total population.

Improving lifestyle and health conditions may significantly reduce the risk of depression.
However, depression remains a multifactorial mental health issue that requires
comprehensive and holistic analysis.

---

## 🗂 Dataset

- **File:** `data/depression_data.csv`
- **Format:** CSV
- **Content includes:**
  - Demographic information
  - Health history indicators
  - Family environment variables
  - Socioeconomic factors
  - Lifestyle-related attributes

The dataset is used for exploratory data analysis (EDA) and visualization purposes.

---

## 🛠 Tools & Skills

- Tableau Desktop / Tableau Public
- Exploratory Data Analysis (EDA)
- Interactive dashboard design
- Data visualization & storytelling

---

## 📄 Notes

- This repository contains the Tableau workbook, data files, and dashboard preview images.
- The project is intended for **educational and portfolio purposes only**.
- The analysis highlights associations rather than causal relationships
  and does not constitute medical advice.
