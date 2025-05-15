# 🛳 Titanic Passenger Age Distribution Analysis

## 📌 Project Description
This project examines the age distribution of Titanic passengers based on gender and survival status. We tested the hypothesis that passenger age is distributed similarly across four categories:

- Survived men
- Deceased men
- Survived women
- Deceased women

## 📊 Dataset
We used the [Titanic dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset/data), which contains passenger information.

## 🔎 Analysis Steps:
1. Grouping passengers by gender and survival status.
2. Checking the normality of age distribution for each group.
3. Selecting an appropriate statistical test:
   - **T-test or ANOVA**, if the distribution is normal.
   - **Binomial test**, if the distribution is not normal.
4. Conducting the binomial test → p-value > 0.05 → no statistically significant differences.

## 🛠 Technologies Used
- Python (Pandas, NumPy, SciPy)
- Jupyter Notebook
- 
## 📌 Key Findings
- Age distribution **is not normal** (p-value > 0.05).
- This means that passenger age across different categories is **not uniformly distributed**.
