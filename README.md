# Prepared by
## Riswana-haris007
### 🧮 Student Performance Dataset Analysis
📌 Overview

This project analyzes student academic performance based on demographic and socioeconomic factors such as:

Gender

Race/Ethnicity

Parental education level

Lunch type (standard vs free/reduced)

Test preparation course status

Math, Reading, and Writing scores

The goal is to identify relationships and trends that influence student academic outcomes.

📁 Dataset Description
Attribute	Description
gender	Male / Female
race/ethnicity	Student group (A–E)
parental level of education	Highest parental education
lunch	Standard vs free/reduced
test preparation course	Completed vs none
math score	0–100
reading score	0–100
writing score	0–100
🧹 Data Preprocessing

Removed duplicates

Standardized text formatting

Converted categorical features to consistent lowercase labels

Validated score ranges (0–100)

Checked and handled missing values (if any)

🔍 Planned Analysis
Statistical Summary

Mean, median, mode, and standard deviation of scores

Score distribution by gender

Score comparison by race group

Boxplots of score variations

Correlation Analysis

Relationship between parental education & student performance

Effect of lunch type (economic status indicator)

Impact of test preparation course completion

Visualization Ideas

Average scores by gender

Average scores by race group

Score improvements with test preparation

Heatmap correlation (math vs reading vs writing)

🧠 Insights to Explore

Some expected hypotheses (to be validated):

Students who completed test preparation tend to score higher

Higher parental education may correlate with better academic performance

Students with free/reduced lunch may score lower on average due to socioeconomic factors

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📌 Example Code Snippet
import pandas as pd

df = pd.read_csv("student_scores.csv")
df.describe()

📊 Expected Output Insights

Comparison of mean scores by gender

Performance ranking across racial/ethnic groups

Trend analysis on preparation courses

Identification of low-performing demographic clusters

🧾 License

This dataset and analysis are for educational research and exploratory analytics.

👩‍💻 Author

Riswana
Data Analytics | Python | Research & Insights

If you want, I can also:
✔ create EDA notebook
✔ build visualizations
✔ compute statistical correlations
✔ create a final report PDF
✔ prepare a presentation or dashboard

Just tell me what you want next.
