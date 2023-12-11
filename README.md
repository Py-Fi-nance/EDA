# EDA
# Exploratory Data Analysis (EDA)

This report provides an in-depth Exploratory Data Analysis (EDA) of a dataset containing bank customer information. The analysis was conducted using Python and its libraries, such as Pandas, NumPy, and Seaborn.

## Table of Contents

- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Insights and Observations](#insights-and-observations)
- [Contributing](#contributing)
- [Contact information](#contact-information)

## Data Preprocessing

1. **Loading Data**: The dataset was loaded into a Pandas DataFrame from 'bank_customer_data.csv'.
2. **Initial Exploration**: The first few rows (`head`) and summary statistics (`describe`) were examined.
3. **Handling Missing Values**: Missing values were identified using `isnull().sum()` and filled with the median for numerical columns.
4. **Outlier Detection and Handling**: Outliers in the 'Balance' column were detected and handled using the Interquartile Range (IQR) method.
5. **Duplicate Entries**: Duplicate rows were removed using `drop_duplicates`.
6. **Standardizing Text Data**: The 'Job' column was standardized to lower case.

## Exploratory Data Analysis

1. **Age Distribution**: The age distribution of customers was visualized using a histogram with kernel density estimation (KDE).
2. **Job Categories**: The distribution of customers across different job categories was displayed using a count plot.
3. **Account Balance Distribution**: The distribution of account balances was visualized using a box plot.
4. **Marital Status Distribution**: The marital status of customers was illustrated using a count plot.
5. **Correlation Matrix**: A heatmap was created to show the correlations between different variables.

## Insights and Observations

The EDA provided valuable insights into the demographics, financial status, and other characteristics of the bank's customers. Observations include the predominant age group, common job categories, distribution of account balances, marital status proportions, and correlations between variables. These insights are crucial for the bank to tailor its services, marketing strategies, and customer engagement approaches more effectively.

## Contributing
We welcome contributions to this project. To contribute:

Fork the project.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.
## Contact Information
For any questions or inquiries, please contact support@pyfi.com - Subject: Github Repo Q,EDA. For a full article walkthrough please visit > https://www.pyfi.com/blog < where you'll also be able to pick up a complimentary copy of the complete, Volume I text of our Machine Learning Edge Blueprint, a $49 value. This text will walk you through everything you need to get started coding Python for Finance Follow on LinkedIn
[![Follow on LinkedIn](https://img.shields.io/badge/Follow%20on-LinkedIn-blue?style=social&logo=linkedin)](https://www.linkedin.com/company/pyfi/)
