# 📊 TASK - 2 : Project 3: Correlation Heatmap & Pairwise Relationships

This project is part of my **Data Science Internship at Syntecxhub**. The objective is to perform **Exploratory Data Analysis (EDA)** by analyzing relationships between numerical features using **Pearson Correlation**, **Heatmaps**, and **Pairplots**.

---

## 📌 Objective

The primary goals of this project are to:

- Compute Pearson Correlation between numerical features.
- Visualize the correlation matrix using a Heatmap.
- Display Pairwise Relationships using Pairplots.
- Identify the strongest positive and negative correlations.
- Understand how different numerical variables are related.

---

## 📂 Dataset

**Dataset Name:** Students Performance Dataset

The dataset contains information about students' academic performance along with demographic and educational attributes.

### Features

| Feature | Type |
|---------|------|
| Gender | Categorical |
| Race/Ethnicity | Categorical |
| Parental Level of Education | Categorical |
| Lunch | Categorical |
| Test Preparation Course | Categorical |
| Math Score | Numerical |
| Reading Score | Numerical |
| Writing Score | Numerical |

Only the numerical columns were used for correlation analysis.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 📚 Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 📈 Project Workflow

### 1. Import Libraries

Required libraries were imported for data analysis and visualization.

---

### 2. Load Dataset

The CSV dataset was loaded into a Pandas DataFrame.

---

### 3. Data Exploration

Performed basic data inspection:

- Display first five rows
- Check dataset information
- Check missing values
- Select numerical columns

---

### 4. Pearson Correlation

Computed Pearson Correlation Matrix using

```python
df.corr()
```

Pearson Correlation values range from:

| Value | Meaning |
|-------|----------|
| +1 | Perfect Positive Correlation |
| 0 | No Correlation |
| -1 | Perfect Negative Correlation |

---

### 5. Correlation Heatmap

Created a Heatmap to visualize the relationships between numerical features.

Features included:

- Annotated values
- Upper triangle masked
- Color mapping using `coolwarm`

---

### 6. Pairplot

Generated Pairplots to visualize pairwise relationships among numerical features.

The pairplot displays:

- Scatter plots
- Distribution plots
- Relationship between every pair of numerical variables

---

### 7. Correlation Analysis

The strongest positive and negative correlations were identified by sorting the Pearson Correlation values.

---

## 📊 Results

From the analysis:

- Reading Score and Writing Score show the strongest positive correlation.
- Math Score is positively correlated with both Reading Score and Writing Score.
- No strong negative correlations were observed in the dataset.

These results indicate that students performing well in one subject generally perform well in the other academic subjects.

---

## 📁 Project Structure

```

├── StudentsPerformance.csv
├── Project3.ipynb
├── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```
git clone https://github.com/yourusername/your-repository.git
```

2. Install dependencies

```
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook or Google Colab.

4. Upload the dataset.

5. Run all cells sequentially.

---

## 📷 Output

The notebook generates:

- Dataset Preview
- Dataset Information
- Missing Value Analysis
- Pearson Correlation Matrix
- Correlation Heatmap
- Pairplot
- Strongest Positive Correlations
- Strongest Negative Correlations

---

## 🎯 Learning Outcomes

Through this project I learned:

- Exploratory Data Analysis (EDA)
- Pearson Correlation Analysis
- Feature Relationships
- Heatmap Visualization
- Pairplot Visualization
- Data Interpretation using Seaborn
- Data Analysis using Pandas

---

## 🚀 Future Improvements

Possible enhancements include:

- Correlation analysis on larger datasets
- Feature Engineering
- Interactive visualizations using Plotly
- Correlation analysis after preprocessing categorical variables
- Machine Learning model based on selected features
