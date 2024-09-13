# Diwali Sales Data Analysis

## Overview

This project involves performing an exploratory data analysis (EDA) on Diwali sales data. The objective is to derive meaningful insights regarding customer behavior, sales trends, and product categories. Key factors such as gender, age group, marital status, occupation, and state-wise sales have been analyzed to understand buying patterns and preferences.

## Features

- **Gender-based Analysis**: Compare total sales and purchase patterns between male and female buyers.
- **Age Group Analysis**: Understand buying behavior across different age groups.
- **State-wise Sales Analysis**: Identify which states contribute the most to total sales.
- **Occupation-based Analysis**: Explore sales trends based on customer occupations.
- **Product Category Analysis**: Highlight top-performing product categories and their sales contribution.
- **Top 10 Most Sold Products**: Identify the most frequently ordered products.
  
## Insights

- Female buyers contribute more to total sales and exhibit higher purchasing power compared to males.
- Buyers aged between 26-35 years show the highest engagement in terms of sales.
- Most orders and sales are from the states of Uttar Pradesh, Maharashtra, and Karnataka.
- Married women, particularly in the IT, Healthcare, and Aviation sectors, are major buyers.
- Food, Clothing, and Electronics are the top-selling product categories.

## Technologies Used

- **Pandas**: For data manipulation and analysis.
- **Seaborn & Matplotlib**: For data visualization and generating insightful plots.
- **NumPy**: For numerical operations.

## Data Preprocessing

- Dropped unrelated columns (`Status`, `unnamed1`) and handled null values.
- Converted the `Amount` column to integer data type for further analysis.

## Getting Started

### Prerequisites

To run this project, you need:

- Python 3.x
- Jupyter Notebook (recommended for interactive analysis)
- Libraries: pandas, seaborn, matplotlib, numpy

### Installing the Required Libraries

You can install the necessary libraries using pip:

```bash
pip install pandas seaborn matplotlib numpy
