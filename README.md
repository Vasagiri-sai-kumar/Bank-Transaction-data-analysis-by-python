# Bank Transaction Data Analysis

This project demonstrates how to analyze and visualize bank transaction data using Python. The goal is to extract meaningful insights from transaction records, such as categorizing expenses, detecting trends, and summarizing financial activity.

## Key Features:

- Transaction ID: Unique identifier for each transaction, ensuring traceability.

- Sender Account ID: The account number of the transaction sender.

- Receiver Account ID: The account number of the transaction receiver.

- Transaction Amount: The monetary value involved in the transaction.

- Transaction Type: The type of transaction—Transfer, Withdrawal, or Deposit.

- Timestamp: The exact date and time the transaction occurred.

- Transaction Status: Indicates whether the transaction was successful or failed.

- Fraud Flag: A binary flag indicating whether the transaction was flagged as fraudulent.

- Geolocation (Latitude/Longitude): Geographic coordinates of the transaction, helpful for spatial analysis.

- Device Used: The type of device used for conducting the transaction (Mobile or Desktop).

- Network Slice ID: Identifies the 6G network slice used during the transaction.

- Latency (ms): The delay (in milliseconds) experienced during the transaction.

- Slice Bandwidth (Mbps): The bandwidth available in the network slice used for the transaction.

- PIN Code: A four-digit security code used for the transaction (masked for privacy).

## Features

- Import and clean bank transaction data
- Categorize transactions into meaningful categories (e.g., groceries, utilities, rent, etc.)
- Perform exploratory data analysis (EDA)
- Generate visualizations such as bar charts, pie charts, and time-series plots
- Provide summary statistics and insights

## Prerequisites

Before running the project, ensure you have the following:

- Python 3.7 or later
- A CSV file containing bank transaction data (required columns: `Date`, `Description`, `Amount`)
- The following Python libraries installed:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - Jupyter Notebook (optional, for interactive analysis)

## Example Visualizations

- Monthly spending trends
- Expense category distribution (pie chart)
- Top 5 expense categories
