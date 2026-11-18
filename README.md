# Analysing Pharmaceutical Sales Data

## Project Overview

This project uses Python for analysing pharmaceutical sales data to identify sales trends across different drug categories and understand patterns in pharmaceutical demand.

## Objectives

Analyse pharmaceutical sales data, identify high-performing drug categories, compare sales across selected periods, and explore monthly sales patterns of respiratory drugs.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib

## Data Analysed

- Date
- Drug Category (ATC Codes)
- Daily Sales Quantities
- Year
- Month
- Weekday Name

## Project Workflow

1. Load the pharmaceutical sales dataset using Pandas.
2. Inspect the dataset structure and understand the columns.
3. Check for missing values and duplicate records.
4. Convert the date column into the appropriate datetime format.
5. Calculate total sales quantities for each drug category.
6. Rank drug categories based on total sales.
7. Analyse the top three drug categories in January 2015, July 2016, and September 2017.
8. Identify the drug category with the highest sales in 2017.
9. Calculate average daily sales for each drug category.
10. Analyse monthly sales patterns of respiratory drugs (R03).
11. Create visualizations using Matplotlib.

## Dataset

The project uses the `salesdaily.csv` dataset from Kaggle.

**Source:** [Pharma Sales Data – Kaggle](https://www.kaggle.com/milanzdravkovic/pharma-sales-data)

The dataset contains daily pharmaceutical sales information across eight ATC drug categories.

## How to Run

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   `pip install pandas matplotlib`
3. Download the `salesdaily.csv` dataset from Kaggle.
4. Place the CSV file inside the `data` folder.
5. Open `Pharmaceutical_Sales_Analysis.ipynb` in Jupyter Notebook.
6. Run the notebook cells sequentially.

## Output

- Total sales analysis by drug category.
- Sales ranking across selected months.
- Year-wise sales analysis for 2017.
- Average daily sales comparison.
- Monthly respiratory drug sales analysis.
- Graphs and visualizations representing sales trends.

## Note

The dataset contains ATC drug categories rather than individual drug brand names. Therefore, individual brand-level sales analysis is not possible with the available data.

## Project Page URL

https://roadmap.sh/projects/pharmaceutical-sales-data
