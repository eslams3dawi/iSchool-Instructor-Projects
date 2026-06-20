# Gym Attendance Data Cleaning Project

## Overview

This project is part of the Digital Egypt Cubs Initiative (DECI) Level 2 curriculum.

The goal of this activity is to introduce students to real-world Data Analysis concepts by working with a dataset that contains common data quality issues. Students will inspect the dataset, identify problems, apply a data cleaning pipeline using Pandas, and visualize the cleaned results using Matplotlib.

This project focuses on developing analytical thinking rather than simply writing code.

---

## Learning Objectives

By completing this project, students will be able to:

* Explore and assess raw datasets.
* Identify common data quality issues.
* Understand the importance of data cleaning before analysis.
* Apply data cleaning techniques using Pandas.
* Create data visualizations using Matplotlib.
* Compare analysis results before and after cleaning.

---

## Data Quality Dimensions Covered

The dataset contains examples of the following data quality issues:

### 1. Consistency

Different formatting styles for the same fitness class.

Examples:

* yoga
* Yoga
* YOGA

### 2. Accuracy

Values that are logically incorrect.

Examples:

* Negative membership fees
* Unrealistic attendance values

### 3. Completeness

Missing attendance values that must be handled appropriately.

### 4. Uniqueness

Duplicate records that can affect analysis results.

---

## Dataset

The project uses:

```text
gym_attendance.csv
```

The dataset contains information about:

* Fitness class names
* Number of attendees
* Class fees

---

## Project Workflow

### Step 1 – Load and Assess the Data

Students begin by loading the dataset and inspecting its contents.

Tasks:

* View the dataset
* Detect data quality issues
* Discuss potential cleaning strategies

---

### Step 2 – Build the Cleaning Pipeline

Students implement a complete cleaning pipeline that includes:

#### Consistency Fix

Standardize class names using Title Case.

#### Accuracy Fixes

* Remove negative fee values
* Remove unrealistic attendance outliers

#### Completeness Fix

Fill missing attendance values using the mean attendance of the corresponding fitness class.

#### Uniqueness Fix

Remove duplicate records.

---

### Step 3 – Visualize the Results

Students create a bar chart showing:

```text
Total Attendance by Fitness Class
```

using Matplotlib.

---

### Step 4 – Discussion and Reflection

Students compare results before and after cleaning and discuss:

* Impact of duplicates
* Impact of outliers
* Handling missing values
* Importance of data quality in decision-making

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Google Colab

---

## Expected Outcomes

At the end of this activity, students should be able to:

* Recognize common data quality issues.
* Build a data cleaning workflow.
* Apply basic data preprocessing techniques.
* Create meaningful visualizations.
* Communicate findings based on cleaned data.

---

## Instructor Notes

This activity is designed to encourage discussion and critical thinking.

Students should first identify data quality issues before implementing fixes. The focus should remain on understanding why each cleaning step is necessary and how it affects the final analysis.

---

### Digital Egypt Cubs Initiative (DECI)

Level 2 – Data Analysis Fundamentals

Prepared for educational and training purposes.
