# Crypto Clustering

# Overview

This project demonstrates how to normalize cryptocurrency market data using the StandardScaler module from scikit-learn. The script scales numerical data while preserving the cryptocurrency names (coin IDs) as the index for better readability and further analysis.

# Prerequisites

Ensure you have the following dependencies installed before running the script:

pip install pandas scikit-learn

# Steps Implemented

1. Load and Prepare Data

- The script assumes the market data is stored in a DataFrame named df_market_data.

- The coin_id column (if present) is separated to retain cryptocurrency names.

2. Normalize Data Using StandardScaler

- The script applies StandardScaler to scale numerical features.

- Non-numeric columns such as coin_id are excluded from scaling.

3. Create a Scaled DataFrame

- A new DataFrame is created with the scaled data.

The original column names are retained.

4. Set the Coin ID as Index

- The coin_id column is restored as the index for reference.

5. Display the Scaled DataFrame

- The first few rows of the scaled DataFrame are printed to verify the transformation.

Code Implementation

![image](https://github.com/user-attachments/assets/24679207-402d-4180-bb6d-f55a9d151c11)


# Usage

- Load your cryptocurrency market data into df_market_data.

- Run the script to normalize the numerical data.

- Use the resulting DataFrame for further analysis or visualization.

# Notes

- The script ignores non-numeric columns to prevent errors during scaling.

- Ensure your dataset includes numeric features for meaningful normalization.

# License

This project is open-source and free to use under the MIT License.

