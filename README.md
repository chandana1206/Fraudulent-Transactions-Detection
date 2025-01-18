# Fraudulent-Transactions-Detection
Overview

This project implements a machine learning pipeline to identify fraudulent transactions. It focuses on feature engineering, class imbalance handling, and model performance evaluation to ensure high accuracy and reliability in detecting fraud.

# Dataset

The dataset contains 6,362,620 rows and 10 columns, representing transaction details over a simulated 30-day period.

# Key Columns:

step: Represents hours elapsed in the simulation (1 step = 1 hour).

type: Transaction type (e.g., CASH-IN, CASH-OUT, PAYMENT).

amount: Amount involved in the transaction.

isFraud: Target variable (1 = Fraudulent, 0 = Not Fraudulent).

isFlaggedFraud: Indicates flagged illegal attempts (e.g., transfers exceeding 200,000).

# Features

Feature engineering included:

Transaction Timing: Derived timeOfDay (e.g., Day, Evening, Night).

Behavioral Patterns: Analyzed balances before and after transactions.

One-Hot Encoding: Encoded categorical variables (type, timeOfDay).
