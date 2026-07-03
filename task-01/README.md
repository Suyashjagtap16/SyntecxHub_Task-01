# 📊 Pandas CSV Reader & Basic Analysis

## 📌 Project Overview

This project demonstrates the fundamentals of data analysis using the **Pandas** library in Python. The objective is to read a CSV dataset, perform basic data exploration, compute statistical summaries, filter specific records, and export the processed data into a new CSV file.

The project was completed as part of the **Syntecxhub Data Science Internship - Week 1 (Project 2)**.

---

## 🚀 Features

- Read a CSV file into a Pandas DataFrame
- Display the first and last five rows of the dataset
- Inspect the data types of each column
- Generate summary statistics using `describe()`
- Calculate:
  - Mean
  - Median
  - Minimum
  - Maximum
  - Count
- Filter rows based on a specific condition
- Select required columns
- Slice the first 50 rows of the filtered data
- Export the filtered dataset into a new CSV file

---

## 📂 Dataset

This project uses the **Stats NZ Business Financial Data** dataset.

The dataset contains business financial statistics including:

- Sales (operating income)
- Operating profit
- Industry information
- Quarterly financial records
- Business performance indicators

---

## 🛠 Technologies Used

- Python 3
- Pandas
- Google Colab

---

## 📁 Project Structure

```
Project/
│
├── task01.ipynb
├── data.csv
├── filtered_sales_data.csv
└── README.md
```

---

## 📖 Steps Performed

### 1. Import Libraries

Imported the Pandas library for data analysis.

### 2. Load Dataset

Loaded the CSV dataset into a Pandas DataFrame.

### 3. Data Exploration

Displayed:

- First 5 rows
- Last 5 rows
- Data types

### 4. Statistical Analysis

Calculated:

- Mean
- Median
- Minimum
- Maximum
- Count

Also generated descriptive statistics using the `describe()` function.

### 5. Data Filtering

Filtered the dataset to include only rows where:

```
Series_title_1 = Sales (operating income)
```

### 6. Column Selection

Selected the following columns:

- Period
- Data_value
- Series_title_1
- STATUS

### 7. Data Slicing

Extracted the first 50 rows from the filtered dataset.

### 8. Export Results

Saved the processed data as:

```
filtered_sales_data.csv
```

---

## 📊 Sample Output

The program displays:

- Dataset preview
- Dataset information
- Summary statistics
- Filtered records
- Confirmation message after exporting the CSV file

---

## 🎯 Learning Outcomes

Through this project, I learned how to:

- Read CSV files using Pandas
- Work with DataFrames
- Explore datasets
- Perform basic statistical analysis
- Filter and slice data
- Select specific columns
- Export processed data to CSV files

---

## 📌 Conclusion

This project provides a beginner-friendly introduction to data analysis using Pandas. It demonstrates the complete workflow of loading a dataset, analyzing it, extracting useful information, and saving the processed results for further use.

---

## 👨‍💻 Author

Suyash Jagtap

#
