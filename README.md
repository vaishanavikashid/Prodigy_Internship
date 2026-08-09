# Prodigy_Internship-Task-02
# 🏠 Gurgaon Real Estate Data Analysis — Task 02

## 📌 Project Overview

This project was completed as part of my **Data Science Internship at Prodigy InfoTech**.

The objective of this task was to perform **data cleaning and Exploratory Data Analysis (EDA)** on a real-world Gurgaon real estate dataset.

The analysis focuses on understanding property prices, BHK distribution, property types, area, rate per square foot, and relationships between numerical variables.

---

## 🎯 Objectives

- Clean and preprocess the real estate dataset
- Handle missing and abnormal values
- Convert data into appropriate data types
- Explore patterns and distributions in the dataset
- Analyze relationships between different variables
- Identify trends and insights using data visualization

---

## 📂 Dataset

The dataset contains information about properties in Gurgaon, including:

- Price
- Status
- Area
- Rate per Sqft
- Property Type
- Locality
- Builder Name
- RERA Approval
- BHK Count
- Society
- Company Name
- Flat Type

### Dataset Source

Sample datasets were provided by Prodigy InfoTech:

https://github.com/Prodigy-InfoTech/data-science-datasets

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Checked for missing values
- Identified abnormal BHK values
- Treated unrealistic BHK values above 10 as missing
- Converted `Price` from object to numeric
- Removed commas from `Rate per sqft`
- Converted `Rate per sqft` to numeric
- Checked for duplicate records
- Removed the record with missing property price
- Verified numerical column data types
- Investigated potential outliers in Area, Price, and Rate per Sqft

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

### 1. Price Distribution

Analyzed the distribution of property prices to understand the overall pricing pattern.

### 2. BHK Distribution

Explored the number of properties across different BHK categories.

The most common category was **3 BHK**, followed by 4 BHK and 2 BHK.

### 3. Property Type Distribution

Analyzed the distribution of different property types such as:

- Apartment
- Plot
- Floor
- Villa
- House
- Penthouse

Apartments were the most common property type in the dataset.

### 4. Property Status

Analyzed properties based on their status:

- Ready to Move
- Under Construction
- New
- Resale

### 5. Area vs Property Price

A scatter plot was used to investigate the relationship between property area and price.

The analysis showed a **positive relationship**, where larger properties generally tend to have higher prices, although there is considerable variation.

### 6. Rate per Sqft vs Property Price

The relationship between rate per square foot and total property price was explored using a scatter plot.

### 7. Correlation Analysis

A correlation heatmap was created to understand relationships between numerical variables.

---

## 🔍 Key Findings

- **3 BHK properties** were the most common in the dataset.
- **Apartments** were the dominant property type.
- Property price showed the strongest correlation with **Rate per Sqft (0.62)**.
- **BHK Count** had a moderate positive correlation with Price (**0.32**).
- **Area** had a relatively weak positive correlation with Price (**0.20**).
- Property prices showed considerable variation, including high-value properties.
- Extreme area values were identified and investigated as potential outliers.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Visualizations

The project includes visualizations such as:

- Price Distribution
- BHK Distribution
- Property Type Distribution
- Property Status Distribution
- Area vs Property Price
- Rate per Sqft vs Property Price
- Correlation Heatmap
