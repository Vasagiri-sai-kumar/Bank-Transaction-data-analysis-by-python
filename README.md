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

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bank-transaction-analysis.git
   cd bank-transaction-analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Place your transaction CSV file in the `data` folder and rename it to `transactions.csv`.
2. Run the analysis script:
   ```bash
   python analyze_transactions.py
   ```
3. View the generated reports and visualizations in the `output` folder.

## File Structure

```
├── data
│   └── transactions.csv  # Your input transaction data
├── output
│   └── ...               # Generated visualizations and reports
├── scripts
│   ├── data_cleaning.py  # Functions for data cleaning
│   ├── data_analysis.py  # Functions for analysis and visualization
│   └── categorize.py     # Functions to categorize transactions
├── analyze_transactions.py  # Main script
├── requirements.txt         # List of dependencies
├── README.md                # Project documentation
```

## Example Visualizations

- Monthly spending trends
- Expense category distribution (pie chart)
- Top 5 expense categories

## Customization

To customize transaction categories, edit the `categorize.py` file and update the `CATEGORY_RULES` dictionary with your own rules.

## Contributing

Contributions are welcome! If you have suggestions or find bugs, feel free to open an issue or submit a pull request.
