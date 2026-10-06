# Supermarket Sales Analysis with Python

**Tools:** Python (pandas, matplotlib, seaborn), Jupyter Notebook, Excel, PowerPoint

## Business question

How did a supermarket's orders, sales and profit change from 2014 to 2017, and which categories drive the business?

## Data

9,994 order lines (5,009 orders) from January 2014 to December 2017.
Columns include order and ship dates, ship mode, customer segment, region, state, category, sub-category, sales, quantity, discount and profit.

## Approach

1. Loaded the Excel file into pandas and checked its shape and data types.
2. Added `Price` (sales ÷ quantity) and `Year` columns.
3. Used `groupby` to compare orders, sales and profit by year.
4. Filtered 2017 and charted category share, quantity by category and sub-category performance with matplotlib and seaborn.
5. Built an Excel pivot dashboard and summarised the findings in a PowerPoint deck.

## Key results

| Year | Sales | Profit |
| --- | --- | --- |
| 2014 | 484,247 | 49,544 |
| 2015 | 470,533 | 61,619 |
| 2016 | 609,206 | 81,795 |
| 2017 | 733,215 | 93,439 |

## Insights

- Sales grew 51% from 2014 to 2017, and profit almost doubled.
- Technology is the largest category by sales (836K), ahead of Furniture (742K) and Office Supplies (719K).

## Files

- `Sales_data (1).ipynb` – Python analysis
- `Sales Data.xlsx` – data and pivot dashboard
- `SUPER MARKET DATA.pptx` – presentation of findings
