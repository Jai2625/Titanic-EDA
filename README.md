# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python, Pandas, NumPy, and ydata-profiling. The objective is to understand the structure of the dataset, identify patterns, handle missing values, detect anomalies, and generate insights through statistical analysis and automated profiling.

---

## Learning Outcomes

- Data Cleaning
- Feature Understanding
- Summary Statistics
- Missing Value Analysis
- Automated Profiling
- Data Visualization
- Insight Generation

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- ydata-profiling
- Jupyter Notebook

---

## Dataset

**Titanic Dataset**

The dataset contains passenger information such as:

- Passenger ID
- Passenger Class
- Name
- Sex
- Age
- Ticket Information
- Fare
- Cabin
- Embarkation Port
- Survival Status

---

## EDA Steps Performed

1. Loaded and inspected the dataset.
2. Checked dataset dimensions and structure.
3. Generated summary statistics.
4. Identified missing values.
5. Detected duplicate records.
6. Performed data cleaning and preprocessing.
7. Created visualizations to understand data distributions.
8. Conducted correlation analysis.
9. Generated an automated profiling report using ydata-profiling.
10. Summarized key insights from the analysis.

---

## Key Insights

1. Cabin contains a significant number of missing values.
2. Age contains missing values that require preprocessing.
3. Female passengers had a higher survival rate than male passengers.
4. First-class passengers were more likely to survive than lower-class passengers.
5. Fare distribution contains several high-value outliers.
6. Passenger class strongly influences survival probability.
7. Family size shows a relationship with survival outcomes.
8. Survival depends on multiple demographic and ticket-related factors.

---

## Deliverables

- Titanic_EDA.ipynb
- Titanic-Dataset.csv
- report.html

---

## How to Run

Install required libraries:

```bash
pip install pandas numpy ydata-profiling
```

Generate the profiling report:

```python
from ydata_profiling import ProfileReport

profile = ProfileReport(df)
profile.to_file("report.html")
```

---

## Project Structure

```text
Titanic-EDA/
│
├── README.md
├── Titanic_EDA.ipynb
├── Titanic-Dataset.csv
├── report.html
```

---

## Author

Jai Singh
