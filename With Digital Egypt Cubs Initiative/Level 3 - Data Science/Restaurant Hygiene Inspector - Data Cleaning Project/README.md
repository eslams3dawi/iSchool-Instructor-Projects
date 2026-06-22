# 🧹 Restaurant Hygiene Inspector – Data Cleaning Project

## 📊 Overview

This project is part of a Data Analysis activity where we act as a **city health inspector** responsible for analyzing and cleaning messy restaurant inspection data.

The dataset contains real-world issues such as:
- Missing values
- Inconsistent date formats
- Duplicates
- Mixed text cases
- Invalid numeric values

The goal is to clean the data using **Pandas** and then visualize insights using **Matplotlib**.

---

## 🎯 Objectives

- Practice data cleaning techniques using Pandas
- Handle missing and duplicate values
- Standardize text and date formats
- Convert incorrect data types
- Perform basic data visualization

---

## 📁 Dataset Features

| Column | Description |
|--------|------------|
| Restaurant | Name of the restaurant |
| Inspection Date | Date of inspection (multiple formats) |
| Hygiene Score | Score of cleanliness (0–100) |
| City | City name (inconsistent casing) |
| Violations | Number of violations (may contain text like "three") |

---

## 🧼 Data Cleaning Steps

### 1. Load Data
- Create a Pandas DataFrame from raw data

### 2. Inspect Data
- `.head()`
- `.info()`
- `.isnull().sum()`
- Check duplicates

### 3. Clean Data
- Remove duplicate rows
- Strip spaces and normalize city names (lowercase)
- Convert inspection dates to datetime format
- Convert hygiene scores to numeric and fill missing values with median
- Fix violations column (e.g., `"three"` → `3`)

### 4. Handle Missing Values
- Drop rows with missing Restaurant or Inspection Date
- Fill remaining missing values using median

### 5. Encoding
- Apply one-hot encoding to the `City` column

---

## 📊 Visualization

- Create a **bar chart** showing average Hygiene Score per Restaurant
- Display only **top 5 restaurants**
- Add:
  - Title
  - Axis labels
  - Legend (if needed)

---

## 🛠️ Tools Used

- Python 🐍
- Pandas 📊
- Matplotlib 📈
- Google Colab