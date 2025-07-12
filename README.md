
# 🍽️ Zomato Data Analysis Project

This project presents an exploratory data analysis (EDA) of a Zomato restaurant dataset using Python. The goal is to uncover insights into customer preferences, restaurant types, and ratings across various dining categories.

## 📊 Features

- Data cleaning and preprocessing (e.g. handling missing values, parsing ratings)
- Exploratory visualizations using **Seaborn** and **Matplotlib**
- Aggregated analysis of:
  - Restaurant types (`listed_in(type)`)
  - Customer votes and ratings
- Key insights drawn from visual trends

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📌 Insights

- Majority of customers prefer **dining** category restaurants.
- Voting patterns and ratings help identify popular restaurant types.

## 📁 Dataset

The project uses a CSV dataset titled `"Zomato data .csv"` (assumed to be available locally in the same directory as the notebook).
- <a href="https://github.com/Ramchandrakanade/Zomato-Data-Analysis-Dashboard/blob/main/Zomato%20data%20.csv">ExcelDataset</a>


##Question (KPIs)
1) What type of restaurant do the majority of customers order from?
2 How many votes has each type of restaurant received from customers?
3) What are the ratings that the majority of restaurants have received?
4)Zomato has observed that most couples order most of their food online. What is their 
average spending on each order?
5) Which mode (online or offline) has received the maximum rating?
6) Which type of restaurant received more offline orders, so that Zomato can provide those 
customers with some good offers?

- Dashboard Interaction <a href="https://github.com/Ramchandrakanade/Zomato-Data-Analysis-Dashboard/blob/main/visuvalization%20images.pdf">View Dashboard</a>

## 🔍 Key Steps

1)Data Loading – Imported the dataset from CSV.

2)Data Cleaning – Handled missing values and transformed rating data.

3)Exploratory Data Analysis – Visualized trends in ratings, cuisines, and locations.

4)Insights – Identified popular food types, high-rated areas, and pricing patterns.

## Dashboard

[screenshot visavulation.pdf](https://github.com/user-attachments/files/21194577/screenshot.visavulation.pdf)



## 🚀 Getting Started

1. Clone this repository
2. Make sure the dataset (`Zomato data .csv`) is available
3. Run the Jupyter Notebook

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook
```
