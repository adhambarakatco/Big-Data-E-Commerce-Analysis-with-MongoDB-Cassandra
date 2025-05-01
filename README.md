# Big Data E-Commerce Analysis with MongoDB & Cassandra

This repository contains the implementation of a Big Data assignment for the "Big Data & NoSQL Databases" course at the German International University of Applied Sciences. The task involves working with a dataset of transaction records from an e-commerce platform and performing various data preprocessing, analysis, and queries using MongoDB and Cassandra.

## Assignment Overview

The dataset contains transaction records that include information about customer purchases, such as invoice numbers, stock codes, product descriptions, quantities, invoice dates, unit prices, customer IDs, and country locations. The goal is to analyze and visualize the dataset with the following tasks, implemented using MongoDB and Cassandra.

### Main Tasks:
1. **Data Preprocessing**: Read, explore, and preprocess the dataset to make it suitable for analysis.
2. **NoSQL Databases**: Insert the cleaned data into MongoDB and Cassandra.
3. **Feature Engineering**: Create a new field `TotalCost = Quantity * UnitPrice` and extract time-based features (categorize `InvoiceDate` into Morning, Afternoon, Evening, and Night).
4. **Top 5 Most Sold Products**: Identify the top 5 products (StockCode) based on quantity sold.
5. **Revenue per Country**: Calculate the total revenue generated per country.
6. **Most Common Purchase Time per Country**: Find the most common purchase time of the day per country.
7. **Average Purchase Amount per Customer**: Calculate the average amount spent per customer.
8. **Top 5 Customers by Spend**: Identify the top 5 customers who have spent the most.
9. **Most Commonly Purchased Product per Time of Day**: Find the most commonly purchased product during each part of the day.

### Bonus Task:
- **Country vs Quantity Correlation**: Investigate if there is a correlation between country and the quantity of purchases, and visualize the findings.

## Dataset Description

The dataset used for this project is an **E-commerce Retail Data** that includes transaction records.

| Column      | Type     | Description                                                 |
|-------------|----------|-------------------------------------------------------------|
| InvoiceNo   | Object   | A code used to identify the invoice                         |
| StockCode   | Object   | A code used to identify the product purchased               |
| Description | Object   | A brief description of the product purchased                |
| Quantity    | Numeric  | The amount of the product purchased                         |
| InvoiceDate | Object   | The date and time the purchase was made                     |
| UnitPrice   | Numeric  | The price of one unit of the product purchased              |
| CustomerID  | Numeric  | The unique identifier for the customer                      |
| Country     | String   | The country where the customer is located                   |

## Technologies Used:
- **MongoDB**: A NoSQL database used for storing and querying data.
- **Cassandra**: A distributed NoSQL database for handling large-scale data.
- **Python**: The programming language used for data manipulation and analysis, with libraries such as Pandas, NumPy, and Matplotlib for data processing and visualization.
- **Jupyter Notebooks**: Used for implementing the code, performing analysis, and generating outputs.

## Google Colab Notebook
You can view and run the notebook directly in Google Colab using the following link:

[Big Data E-Commerce Analysis Notebook](https://colab.research.google.com/drive/189Fj3aYVRZvlxN2yBQTpxBFsJYhL7S6N?usp=sharing)

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/big-data-ecommerce-analysis.git

2. Install the required Python dependencies:
   ```bash
    pip install -r requirements.txt

3. Set up MongoDB and Cassandra databases and ensure they are running.

4. Follow the instructions in the Jupyter Notebook to load the dataset, perform the analysis, and generate the required outputs.

How to Run
1. Preprocess the Dataset: The notebook will guide you through reading and preprocessing the Online Retail.csv file.

2. Data Insertion: Insert the cleaned data into MongoDB and Cassandra using Python.

3. Run Queries: Execute the queries to perform the required analysis, such as finding the most sold products or calculating total revenue per country.

4. Visualization: Use Python's visualization libraries to generate insights from the data, such as country vs quantity correlation.

Deliverables:
Code: Implemented in Jupyter Notebooks

Zip file: Containing the notebook and necessary files, which will be submitted via email.

Notes:
This assignment is completed in pairs, and each team member's name and ID must be included in the submission.

Plagiarism is strictly prohibited. Evaluation will be done based on your reasoning and implementation.

License:
This project is licensed under the MIT License - see the LICENSE file for details.
