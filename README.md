# 🌍 Egypt - Red Sea Earthquake Analysis (1955–2024)

## 📌 Project Overview
This project analyzes earthquake activity in the Egypt–Red Sea region over nearly 70 years (1955–2024). The goal is to understand seismic patterns, trends, and relationships between earthquake characteristics such as magnitude, depth, and frequency.

The analysis combines data preprocessing, visualization, and statistical testing to answer key research questions about how earthquake activity has evolved over time.

---

## 📊 Dataset
- Source: Kaggle (Egypt-RedSea Earthquake Dataset)
- Records: 473 earthquake events
- Time Range: 1955 – 2024
- Features: 15 columns

### Key Columns:
- time – Date & time of earthquake
- latitude, longitude – Location
- depth – Depth (km)
- mag_Mw – Magnitude
- distance_from_cairo_km – Distance from Cairo
- Engineered features (recent activity, rolling averages)

---

## ❓ Research Questions
1. How has earthquake frequency changed over time?
2. Is there a relationship between earthquake depth and magnitude?

---

## 🧪 Hypotheses

### Hypothesis 1: Earthquake Frequency
- H0: No difference between 1955–1989 and 1990–2024
- H1: More earthquakes occurred in 1990–2024

### Hypothesis 2: Depth vs Magnitude
- H0: No relationship
- H1: Shallower earthquakes are stronger (negative correlation)

---

## ⚙️ Project Workflow

### 1. Data Preparation
- Converted time to datetime
- Extracted year, month, decade
- Created magnitude categories

### 2. Data Analysis
- Summary statistics
- Distribution analysis
- Time-series trends
- Spatial analysis

### 3. Statistical Testing
- Chi-Square Test
- Pearson Correlation
- Welch’s T-test
- One-way ANOVA

---

## 📈 Key Findings
- Earthquake frequency increased significantly after 1990
- Most earthquakes are between 3.5 – 4.5 Mw
- Weak positive correlation between depth and magnitude

---

## ⚠️ Limitations
- Older data may be underreported
- Dataset dominated by recent decades
- No geological variables included
- Correlation does not imply causation

---

## 🧰 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## 📂 Project Structure
```
dataset/
notebook/
report/
README.md
```

---

## 👥 Contributors
- Mostafa Mattar
- Wael Amin
- Ziad Atia
- Seif Eldeen

---

## 🚀 How to Run
1. Clone the repository
2. Install dependencies: pandas, numpy, matplotlib, seaborn, scipy
3. Open the Jupyter notebook

---

## 📌 Conclusion
Earthquake activity increased in recent decades, while depth shows only a weak relationship with magnitude.
