
# Housing Market Dataset Creation

This project involves the creation of a fictional housing market dataset using Python and the Pandas library. The dataset includes information about the number of bedrooms, bathrooms, and price per square meter for 100 houses.

## Project Overview

This repository contains Python code for creating a housing market dataset using the Pandas library. The analysis includes steps to generate random series for bedrooms, bathrooms, and prices, then combine them into a DataFrame. The primary goals of this project are:

- Generate random series for the number of bedrooms, bathrooms, and price per square meter.
- Combine the generated series into a DataFrame with columns: 'bedrs', 'bathrs', 'price_sqr_meter'.
- Create a single-column DataFrame ('bigcolumn') by concatenating the generated series along rows.
- Reindex 'bigcolumn' to ensure it goes from index 0 to 299.

## Analysis Steps

1. Import the necessary libraries, including Pandas and NumPy.
2. Generate three different series of random numbers:
   - 'series1' with random numbers from 1 to 4.
   - 'series2' with random numbers from 1 to 3.
   - 'series3' with random numbers from 10,000 to 30,000.
3. Create a DataFrame 'df' by concatenating the three series along columns.
4. Rename the columns of 'df' to 'bedrs', 'bathrs', and 'price_sqr_meter'.
5. Create a one-column DataFrame 'bigcolumn' by concatenating the three series along rows and ignoring the index.
6. Check if 'bigcolumn' only goes up to index 99 using the 'index' attribute.
7. Reindex 'bigcolumn' to ensure it goes from index 0 to 299.

## Repository Structure

```
Housing-Market-Dataset-Creation/
│
├── housing_market.ipynb  # Jupyter Notebook containing dataset creation code
└── readme.md              # Project overview and details
```

## Usage

1. Clone the repository using: `git clone https://github.com/your-username/Housing-Market-Dataset-Creation.git`
2. Navigate to the repository: `cd Housing-Market-Dataset-Creation`
3. Open the `housing_market.ipynb` notebook to access the detailed dataset creation steps and results.

## Acknowledgments

- Thanks to the creators and contributors of the Pandas and NumPy libraries for enabling data manipulation and generation.

---
