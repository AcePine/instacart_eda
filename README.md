# Instacart Market Basket Analysis

This project involves the analysis of Instacart customer shopping habits using data provided by Instacart for a Kaggle competition in 2017. The data includes information about orders, products, order details, departments, aisles, and more.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Preparation](#data-preparation)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Analysis Questions](#analysis-questions)
- [Repository Contents](#repository-contents)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Instacart is a grocery delivery and pick-up service that allows customers to shop for groceries online and have them delivered to their doorstep. In this project, we aim to gain insights into customer shopping behaviors by analyzing the provided Instacart dataset.

## Data Preparation

The data for this project is divided into several tables, including:
- `orders`: Information about customer orders, order numbers, day of the week, order hour, and days since the prior order.
- `products`: Details about the products, including product name, aisle, and department.
- `order_products`: Information about products added to carts, including the order ID and product ID.
- `aisles` and `departments`: Tables containing information about the store's aisles and departments.

## Data Cleaning

Data cleaning was performed to ensure data quality:
- Duplicated rows in all data tables were identified and removed.
- Missing values were dealt with by filling in missing product names with "Unknown."
- Missing values in the 'add_to_cart_order' column of the 'order_products' table were replaced with 999 and converted to integers.

## Exploratory Data Analysis (EDA)

In this project, we performed EDA to understand various aspects of the Instacart data:
- Checked the distribution of 'order_hour_of_day' and 'order_dow' values to verify their sensibility.
- Analyzed the time of day when customers typically shop for groceries.
- Explored the day of the week when customers place orders.
- Investigated the days customers typically wait before placing another order.
- Compared the 'order_hour_of_day' distributions between Wednesdays and Saturdays.
- Examined the distribution of the number of orders per customer.
- Identified the top 20 popular products.

## Analysis Questions

This project also aimed to answer specific analysis questions:
- How many items do people typically buy in one order?
- What does the distribution of items per order look like?

## Repository Contents

- `instacart_analysis.ipynb`: A Jupyter Notebook containing the Python code used for data analysis and visualization.
- `datasets/`: A folder containing the dataset files used in the project.
- `README.md`: The README file that you are currently reading.

## Usage

To replicate or build upon this analysis, you can:
1. Clone this GitHub repository.
2. Run the Jupyter Notebook `instacart_analysis.ipynb` using your preferred Python environment.

## Contributing

Contributions to this project are welcome. Feel free to open an issue or submit a pull request if you have any improvements or suggestions.
