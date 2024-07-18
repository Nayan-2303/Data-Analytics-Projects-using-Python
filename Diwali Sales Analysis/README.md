# Diwali Sales Data Analysis

This project involves analyzing a dataset of Diwali sales to gain insights into the purchasing behavior of customers. The analysis covers various aspects such as gender, age, state, marital status, occupation, and product categories.

## Getting Started

These instructions will help you understand how to run the code and what each section does.

### Prerequisites

Ensure you have the following Python libraries installed:

- numpy
- pandas
- matplotlib
- seaborn

You can install them using pip:

```bash
pip install numpy pandas matplotlib seaborn
```

### Dataset

The dataset used in this analysis is `Diwali Sales Data.csv`. Make sure this file is in the same directory as your script.

### Procedure

1. **Import Libraries**: The necessary libraries are imported for data manipulation and visualization.

2. **Load Dataset**: The dataset is loaded using `pd.read_csv()` function.

3. **Initial Exploration**:
   - The shape of the dataset is checked to understand its dimensions.
   - The first few rows of the dataset are displayed using `df.head()`.
   - Basic information about the dataset is obtained using `df.info()`.

4. **Data Cleaning**:
   - Unrelated or blank columns (`'Status'`, `'unnamed1'`) are dropped.
   - Null values are checked and dropped.
   - The data type of the 'Amount' column is changed to integer.

5. **Column Renaming**: The column `'Marital_Status'` is renamed to `'Shaadi'`.

6. **Descriptive Statistics**:
   - The `df.describe()` method is used to get descriptive statistics for the dataset.
   - Descriptive statistics for specific columns (`'Age'`, `'Orders'`, `'Amount'`) are obtained.

7. **Exploratory Data Analysis (EDA)**:
   - **Gender**:
     - A bar chart is plotted for the count of each gender.
     - A bar chart is plotted for the total amount spent by each gender.
   - **Age**:
     - A bar chart is plotted for the count of each age group, with gender as the hue.
     - A bar chart is plotted for the total amount spent by each age group.
   - **State**:
     - A bar chart is plotted for the total number of orders from the top 10 states.
     - A bar chart is plotted for the total amount of sales from the top 10 states.
   - **Marital Status**:
     - A bar chart is plotted for the count of each marital status.
     - A bar chart is plotted for the total amount spent by marital status, with gender as the hue.
   - **Occupation**:
     - A bar chart is plotted for the count of each occupation.
     - A bar chart is plotted for the total amount spent by each occupation.
   - **Product Category**:
     - A bar chart is plotted for the count of each product category.
     - A bar chart is plotted for the total amount spent on each product category.
   - **Product ID**:
     - A bar chart is plotted for the top 10 most sold products by order count.
     - Another bar chart is plotted for the top 10 most sold products by order count using a different method.

8. **Conclusion**: Based on the analysis, key insights are summarized:
   - Married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are more likely to buy products from the Food, Clothing, and Electronics categories.

## Running the Code

To run the code, simply execute the script in your Python environment. The visualizations will be displayed, providing insights into the dataset.

