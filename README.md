# Sales Data Analysis Using Python

## Project Overview

This project demonstrates fundamental data analysis skills using Python and pandas. It explores sales transactions to identify revenue trends, compare product performance, and analyze revenue distribution across categories.

The analysis is based on a small, synthetic dataset created for educational purposes.

## Dataset

The dataset contains 10 sales transactions from January to March 2024.

**Columns:**
- `order_id` — unique transaction identifier
- `date` — transaction date
- `product` — product identifier (A, B, C)
- `category` — product category (Tech or Home)
- `price` — unit price
- `quantity` — number of units sold

## Tools and Technologies

- Python
- pandas — data manipulation and aggregation
- Matplotlib — data visualization
- Jupyter Notebook — interactive analysis

## Analysis Performed

1. Created and explored a sales dataset using pandas.
2. Calculated revenue using unit price and quantity.
3. Aggregated revenue by month to examine sales trends.
4. Compared revenue across product categories.
5. Analyzed individual product performance.
6. Created basic visualizations to communicate the results.

## Key Findings

| Metric | Result |
|---|---|
| Total revenue | 2,250 |
| January revenue | 600 |
| February revenue | 800 |
| March revenue | 850 |
| Tech category revenue share | 80% |
| Highest-revenue product | Product B (1,000) |
| Product with the most orders | Product A (5 orders) |

Revenue increased throughout the three-month period, although the growth rate slowed between February and March.

Product B generated the highest revenue, while Product A appeared in the largest number of transactions.

## How to Run

1. Download or clone this repository.
2. Install the required Python libraries: `pandas`, `matplotlib`, and `notebook`.
3. Open `notebook/Sales Analysis Project.ipynb` in Jupyter Notebook or VS Code.
4. Run all cells in order.

The notebook creates a small sales dataset and saves it as a CSV file in the `data` directory.

## Limitations

This is an introductory data analysis project using only 10 artificially generated transactions. The findings demonstrate analytical techniques and should not be interpreted as statistically representative business insights.
