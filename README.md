

#  Movie Budget vs Revenue Analysis with Seaborn & Linear Regression

This Jupyter notebook is designed for learners who want to practice data analysis, data cleaning, visualization, and linear regression using **Pandas**, **Seaborn**, **Matplotlib**, and **Scikit-learn**. It explores whether higher film production budgets lead to higher box office revenues.

---

## 📁 Dataset Information

The dataset contains scraped information (as of May 1, 2018) from [the-numbers.com](https://www.the-numbers.com/), covering:

- Movie Titles
- Release Dates
- Production Budgets
- Domestic Gross Revenue
- Worldwide Gross Revenue

---

## 📊 What You'll Learn

### 🔹 Data Cleaning
- Removing `$` and `,` from monetary values
- Handling missing values
- Converting columns to numeric and datetime types

### 🔹 Exploratory Data Analysis
- Descriptive statistics using `.describe()` and `.info()`
- Detecting films with zero revenue
- Filtering data by conditions
- Creating subsets: old vs new films

### 🔹 Data Visualization
- Scatter plots and regression lines with `Seaborn`
- Bubble charts by budget and revenue
- Visualizing releases over time

### 🔹 Feature Engineering
- Creating a new column `Decade` from `Release_Date`
- Separating films before and after 1970

### 🔹 Linear Regression
- Using `Seaborn`’s `regplot()` for visual trend analysis
- Applying `scikit-learn` to fit a linear regression model
- Calculating intercept, slope, and R² score
- Predicting revenue from budget

---

## 🧪 Practice Challenges Included

- Identify films that never grossed revenue
- Calculate average, minimum, and maximum statistics
- Filter unreleased films
- Determine percentage of films that lost money
- Visualize production budgets over decades
- Predict revenue for a $350 million budget film

---

## 🔧 Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook or Google Colab

---

## 🚀 Getting Started

1. Clone the repository or download the `.ipynb` notebook.
2. Open it in [Google Colab](https://colab.research.google.com/) or Jupyter Lab.
3. Mount Google Drive if you're using Colab and adjust the dataset path.
4. Run each cell step by step to explore the data and complete the analysis.

---



