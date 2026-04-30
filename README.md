# 🚢 Titanic Survival Analysis

A data analysis project built using Python as part of **Lab Evaluation – 2**
for the course **Programming Essentials for AI and ML (UAI201)**
at **Thapar Institute of Engineering & Technology, Patiala**.

---

## 📌 Project Overview

This project performs a detailed analysis of the Titanic passenger dataset
to identify the key factors that influenced survival during the Titanic disaster
of April 15, 1912. The analysis covers data cleaning, handling missing values,
outlier detection, statistical analysis, and data visualization.

---

## 📂 Dataset

- **Name** — Titanic Dataset
- **Source** — [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **Rows** — 891 passengers
- **Columns** — 12 columns
- **Target Column** — `Survived` (0 = Did Not Survive, 1 = Survived)

### Key Columns:
| Column     | Description                          |
|------------|--------------------------------------|
| Survived   | Whether passenger survived (0/1)     |
| Pclass     | Passenger class (1st, 2nd, 3rd)      |
| Sex        | Gender of passenger                  |
| Age        | Age of passenger                     |
| SibSp      | No. of siblings/spouse aboard        |
| Parch      | No. of parents/children aboard       |
| Fare       | Ticket fare paid                     |
| Embarked   | Port of embarkation (S, C, Q)        |

---

## 🛠️ Tools & Libraries Used

| Tool / Library | Purpose                        |
|----------------|--------------------------------|
| Python         | Programming language           |
| Pandas         | Data loading and manipulation  |
| NumPy          | Numerical calculations         |
| Matplotlib     | Data visualization and graphs  |
| Seaborn        | Heatmap and advanced plots     |

---

## ⚙️ How to Run

**Step 1 — Clone the repository**
```bash
git clone https://github.com/your-username/titanic-survival-analysis.git
cd titanic-survival-analysis
```

**Step 2 — Install required libraries**
```bash
pip install pandas numpy matplotlib seaborn
```

**Step 3 — Download the dataset**

Download `titanic.csv` from [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
and place it in the project folder.

Or load it directly in the code using Seaborn:
```python
import seaborn as sns
df = sns.load_dataset('titanic')
```

**Step 4 — Run the analysis**
```bash
python titanic_analysis.py
```

---
