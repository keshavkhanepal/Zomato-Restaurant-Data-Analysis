# 🍽️ Zomato Restaurant Data Analysis

An Exploratory Data Analysis (EDA) project on Zomato restaurant data using Python. This project aims to uncover customer preferences, restaurant trends, rating patterns, online ordering behavior, and cost-related insights through data visualization and statistical analysis.

---

## 📌 Project Overview

The food delivery and restaurant industry generates a large amount of customer and business data. This project analyzes a Zomato restaurant dataset to identify key factors influencing restaurant popularity, ratings, and customer engagement.

Using Python and data visualization techniques, the project answers several business-oriented questions that can help restaurant owners and decision-makers understand customer behavior and improve service offerings.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing.
- Explore restaurant rating patterns.
- Analyze the impact of online ordering on customer engagement.
- Study restaurant categories and their popularity.
- Examine cost distribution among restaurants.
- Generate actionable business insights from the dataset.

---

## 📂 Dataset Information

The dataset contains information about restaurants listed on Zomato, including:

| Feature | Description |
|----------|-------------|
| name | Restaurant name |
| online_order | Availability of online ordering |
| book_table | Availability of table booking |
| rate | Restaurant rating |
| votes | Number of customer votes |
| approx_cost(for two people) | Estimated cost for two people |
| listed_in(type) | Restaurant category/type |

**Dataset Size:** 148 Rows × 7 Columns

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

### 1. Restaurant Type Distribution
- Identified the most common restaurant categories.
- Compared the frequency of each restaurant type.

### 2. Rating Analysis
- Examined rating distributions.
- Identified highly rated restaurant categories.

### 3. Online Ordering Analysis
- Compared restaurants that offer online ordering with those that do not.
- Evaluated customer engagement through vote counts.

### 4. Cost Analysis
- Studied the distribution of restaurant pricing.
- Compared costs across restaurant categories.

### 5. Customer Engagement Analysis
- Investigated relationships between ratings and votes.
- Identified popular restaurants based on customer feedback.

---

## 📈 Key Insights

- Dining and Buffet restaurants represent a significant portion of the dataset.
- Restaurants with higher ratings generally receive more customer votes.
- Online ordering contributes to increased customer engagement.
- Restaurant pricing varies considerably across categories.
- Customer reviews and ratings play an important role in restaurant popularity.

---

## 📁 Project Structure

```text
zomato-data-analysis/
│
├── data/
│   └── Zomato-data.csv
│
├── notebooks/
│   └── Zomato_Data_Analysis_Using_Python.ipynb
│
├── images/
│   └── visualizations/
│
├── README.md
├── requirements.txt
└── .gitignore
