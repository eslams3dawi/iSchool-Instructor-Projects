# 📊 Movie Madness – Exploring Data Distributions (Data Analysis Project)

---

## 🧠 Overview

This project is part of a Data Analysis activity where we explore a dataset of movie runtimes.  
The goal is to understand how data is distributed, detect skewness, and identify outliers using statistical methods like the IQR method.

---

## 🎯 Objectives

- Create and manipulate Pandas DataFrames  
- Analyze data using `.info()` and `.describe()`  
- Understand distribution shape (mean vs median)  
- Detect outliers using the IQR method  
- Visualize data using Matplotlib  
- Interpret real-world data insights  

---

## 📁 Dataset Description

The dataset contains information about movies and their runtime in minutes.

| Column         | Description                |
|----------------|----------------------------|
| Movie Title    | Name of the movie         |
| Runtime (Min)  | Duration in minutes       |

---

## 📌 Key Concepts Used

### 1. DataFrame Creation
We load the dataset into a Pandas DataFrame for analysis.

---

### 2. Data Exploration

- `.head()` → Preview data  
- `.info()` → Data types and missing values  
- `.describe()` → Statistical summary  

---

### 3. Distribution Analysis

We compare:

- Mean  
- Median  

📌 This helps determine:
- Symmetric distribution  
- Right-skewed (positively skewed)  
- Left-skewed (negatively skewed)  

---

### 4. Outlier Detection (IQR Method)

We use:

- Q1 (25th percentile)  
- Q3 (75th percentile)  
- IQR = Q3 - Q1  

Then calculate:

- Lower Bound = Q1 - 1.5 × IQR  
- Upper Bound = Q3 + 1.5 × IQR  

📌 Any value outside this range is considered an outlier.

---

### 5. Visualization

We use a histogram to visualize runtime distribution:

```python
plt.hist(df["Runtime (Min)"], bins=10)
plt.title("Movie Runtime Distribution")
plt.xlabel("Runtime (Minutes)")
plt.ylabel("Frequency")
plt.show()

plt.show()
```

📊 This shows how movie runtimes are distributed across intervals.

---

### 6. Tools Used
Python 🐍
Pandas 📊
Matplotlib 📉
Google Colab 