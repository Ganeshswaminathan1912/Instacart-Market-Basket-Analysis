# Download the dataset and run the file after installing the packages
https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset

## Project Structure

- `project_F1_C_VL.ipynb`: Main notebook for data loading, cleaning, and exploratory analysis.
- `instacart-market-basket-analysis/`: Directory containing the original dataset CSV files:
  - `aisles.csv`
  - `departments.csv`
  - `orders.csv`
  - `order_products__prior.csv`
  - `order_products__train.csv`
  - `products.csv`

## Features

- Import and inspect various dataset components
- Clean and merge datasets for coherent analysis
- Examine missing values and data types
- Generate summary statistics and initial visualizations

## Setup Instructions

1. Clone this repository.
2. Place the Instacart dataset in a folder named `instacart-market-basket-analysis` at the project root.
3. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
