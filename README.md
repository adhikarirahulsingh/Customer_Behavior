# Customer_Behavior

## Overview

This project focuses on analyzing customer purchase data. The dataset contains information about customer demographics, purchase details, product ratings, and more. The goal is to clean, explore, and analyze the data to extract meaningful insights and visualize them using a Power BI dashboard.

## Dataset

The dataset consists of 3,900 records and 18 columns. Each row represents a customer’s purchase, with details about the customer and the product they purchased. The columns include customer demographics, product details, purchase amount, and other relevant data such as ratings and payment methods.

### Key Columns:

* **Customer ID**: Unique identifier for each customer.
* **Age**: Age of the customer.
* **Gender**: Gender of the customer.
* **Item Purchased**: Name of the purchased item.
* **Category**: Category of the purchased item.
* **Purchase Amount (USD)**: Total amount spent in USD.
* **Location**: Geographical location of the customer.
* **Size**: Size of the purchased item.
* **Color**: Color of the purchased item.
* **Season**: Season during which the purchase was made.
* **Review Rating**: Rating given by the customer for the product.
* **Subscription Status**: Whether the customer is subscribed to a service.
* **Shipping Type**: Type of shipping chosen by the customer.
* **Discount Applied**: Whether a discount was applied to the purchase.
* **Promo Code Used**: Whether a promo code was used.
* **Previous Purchases**: Number of previous purchases by the customer.
* **Payment Method**: Method used for payment.
* **Frequency of Purchases**: How often the customer makes purchases.

## Tools

The following tools and technologies are used in this project:

* **Python**: For data loading, cleaning, and exploratory data analysis (EDA).
* **PostgreSQL**: For querying the dataset stored in a relational database.
* **SQL**: To extract, filter, and aggregate data for analysis.
* **Power BI**: To create an interactive and visually engaging dashboard displaying key insights from the data.

## Steps

1. **Load Data**: The dataset is imported into Python for further analysis.
2. **Perform Exploratory Data Analysis (EDA)**: The dataset is analyzed to understand its structure, distributions, and identify any potential patterns or issues.
3. **Data Cleaning**: Missing values are handled, and data types are corrected as necessary.
4. **Run SQL Queries**: Queries are executed on the PostgreSQL database to extract insights and perform aggregations.
5. **Create Power BI Dashboard**: A dashboard is developed using Power BI to visualize trends, patterns, and key performance metrics.

## Dashboard

The Power BI dashboard provides an interactive, visual representation of the data, including the following features:

* **Interactive Filters**: Users can filter the data by parameters such as `Age`, `Category`, or `Location`.
* **Visualizations**: Includes charts such as bar graphs, line graphs, and pie charts to explore customer behavior, sales trends, and product performance.
* **Key Metrics**: Key performance indicators (KPIs) such as total sales, average review ratings, and frequency of purchases.

## How to Run

1. **Install Required Packages**:

   * Install necessary Python packages for data analysis:

     * `pandas`
     * `numpy`
     * `matplotlib`
     * `psycopg2` (for PostgreSQL connection)
2. **Data Import**:

   * Ensure the dataset is correctly loaded into the Python environment for analysis.
3. **Connect to PostgreSQL**:

   * Set up a connection to the PostgreSQL database to run SQL queries.
4. **Load Power BI**:

   * Open the Power BI file (`.pbix`) and ensure all connections to the data source are properly configured before refreshing the dataset.

## Conclusion

This project demonstrates how to load, clean, analyze, and visualize data using Python, SQL, and Power BI. By creating an interactive dashboard, the project provides valuable insights into customer behavior and purchase trends.

