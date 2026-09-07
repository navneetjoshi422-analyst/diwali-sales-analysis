# Diwali Sales Exploratory Data Analysis (EDA)

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on Diwali sales data to uncover key insights into customer purchasing patterns. By analyzing variables such as gender, age, marital status, and occupation, this project aims to identify the demographics that drive the most sales and generate actionable business intelligence.

## Dataset Information
*   **Source Data:** The analysis is based on a dataset named `Diwali Sales Data.csv`.
*   **Size:** The raw dataset contains 11,251 rows and 15 columns.
*   **Key Features:** `User_ID`, `Cust_name`, `Product_ID`, `Gender`, `Age Group`, `Age`, `Marital_Status`, `State`, `Zone`, `Occupation`, `Product_Category`, `Orders`, `Amount`.

## Key Objectives
The primary goal of this analysis is to understand customer behavior by answering questions such as:
1.  Which gender contributes more to total sales and purchasing power?
2.  Which age groups are the most active buyers?
3.  How does marital status combined with gender impact purchasing behavior?
4.  Which geographic states generate the highest number of orders and total revenue?
5.  Which occupational sectors do the top buyers belong to?
6.  What are the top-selling product categories?

## Tech Stack & Libraries
This project is built using Python and utilizes the following libraries for data manipulation and visualization:
*   **Pandas:** Data manipulation, cleaning, and aggregation.
*   **NumPy:** Numerical operations.
*   **Matplotlib:** Basic data visualization and plotting.
*   **Seaborn:** Advanced statistical data visualization.

## Key Insights & Findings
Based on the exploratory data analysis, the following key trends were discovered:

*   **Gender:** Most buyers are female. Additionally, the total purchasing value (amount spent) by females is significantly greater than that of men.
*   **Age:** The most active buyer demographic falls within the **26-35 age group**, with females in this bracket driving the highest sales.
*   **Marital Status:** Married females constitute the largest customer segment, indicating significant purchasing power within this demographic.
*   **Geography:** **Uttar Pradesh**, **Maharashtra**, and **Karnataka** are the top three states, contributing the highest number of orders and the largest share of total sales amount.
*   **Occupation:** Buyers working in the **IT Sector**, **Healthcare**, and **Aviation** industries are the top spenders.
*   **Product Categories:** The most popular and highest revenue-generating product categories are **Food**, **Clothing**, and **Electronics/Footwear**.

## How to Run the Project
To run this analysis locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/diwali_sales_analysis.git](https://github.com/your-username/diwali_sales_analysis.git)
    cd diwali_sales_analysis
    ```

2.  **Install the required dependencies:**
    Ensure you have Python installed, then run:
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```

3.  **Run the Notebook:**
    Launch Jupyter Notebook in the project directory:
    ```bash
    jupyter notebook
    ```
    Open the `diwali_sales_analysis.ipynb` file and execute the cells sequentially.

---
*Feel free to explore the notebook for detailed visualizations and code!*
