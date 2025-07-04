# 🏥 Hospital Admissions EDA Project

This is a beginner-friendly exploratory data analysis (EDA) project that analyzes patient admission trends in a city hospital. The goal is to improve patient scheduling, reduce wait times, and manage hospital resources more effectively using historical admission data.

---

## 🎯 Objectives

* Perform exploratory data analysis using Pandas and visualization libraries.
* Identify trends in admissions by gender, age, department, and room type.
* Answer key business questions based on patient admission patterns.
* Visualize insights using clear and informative charts.

---

## 🧱 Project Sections

### 1️⃣ Import Libraries & Load Data

Essential libraries like `pandas`, `matplotlib`, and `seaborn` are imported. The dataset is loaded into a DataFrame for analysis.

### 2️⃣ Data Cleaning, Feature Engineering & Type Conversion

Unnecessary spaces in column names are removed, missing values are handled, and date columns are converted. New features like `ADMISSION_DAY`, `ROOM_TYPE`, and `PREVIOUS_VISITS` are engineered.

### 3️⃣ Understand Basic Structure & Clean Data

In this step, I explored the dataset’s structure using .info(), .shape, and .head(), reviewed summary statistics with .describe(), and checked for missing values using .isnull().sum(). This helped ensure the data was complete and ready for deeper analysis.

### 4️⃣ Exploratory Data Analysis

Insightful questions are explored using plots and tables. Various visualization techniques like bar charts, heatmaps, and violin plots are used to present trends.

---

## ❓ Exploratory Questions Answered

1. What is the total number of admissions?
2. What is the distribution of gender among admitted patients?
3. Which age group is most frequently admitted?
4. What are the most common admission types?
5. Which departments have the highest number of admissions?
6. What room type is most frequently assigned?
7. On which day of the week do most patients get admitted?
8. What percentage of patients have visited before (previous\_visits > 0)?
9. Is there a difference in admission types across genders?
10. Create 3 visualizations to represent interesting patterns in the data.

---

## 📁 Files Included

* `HealthCare_EDA_Project.ipynb` – The main Jupyter notebook with full code and visualizations.
* `README.md` – Project overview and documentation.
* `Cleaned_Dataset.csv` – *(Optional, if included)* Dataset used for the project.

---

## 🧠 Skills Learned

* Data Cleaning & Preprocessing
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Insight Communication

---

## 🛠️ Tools & Technologies

* Python 3
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📌 Dataset Source

* [Kaggle - Hospital Admissions Data](https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data)

---

⭐ **Feel free to fork or star this repo if you found it useful!**

---
