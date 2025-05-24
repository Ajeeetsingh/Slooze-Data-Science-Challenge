# Slooze Data Science Challenge
## Dataset Link:
https://drive.google.com/drive/folders/1GA4xd30jnD0OoHVjmR-zeg2upa8fjy47?usp=sharing

## Overview
This repository contains the solution to the Slooze Data Science Challenge, focusing on inventory, purchase, and sales analysis to optimize Slooze's liquor store operations. The project uses a dataset of six CSV files (sales, purchases, inventory, etc.) to perform demand forecasting, inventory classification, and supply chain optimization, delivering actionable insights for inventory management and operational efficiency.

The analysis is implemented in a Google Colab notebook (`Slooze_Data_Science_Challenge.ipynb`) using Python, with libraries like pandas, numpy, matplotlib, seaborn, and Prophet. The notebook includes clear visualizations, tables, and recommendations to support decision-making.

## Features
- **Demand Forecasting**: Predicts future sales for high-demand products using Prophet.
- **ABC Analysis**: Classifies inventory into A/B/C categories based on sales value.
- **EOQ Analysis**: Calculates optimal order quantities to minimize costs.
- **Reorder Point Analysis**: Determines reorder points to prevent stockouts.
- **Lead Time Analysis**: Evaluates supplier lead times for supply chain efficiency.
- **Additional Insights**: Identifies top-performing products, slow-moving stock, and high-sales stores.

## Dataset
The analysis uses six CSV files provided by the challenge:
- `2017PurchasePricesDec.csv`: Product pricing and descriptions.
- `BegInvFINAL12312016.csv`: Beginning inventory.
- `EndInvFINAL12312016.csv`: Ending inventory.
- `InvoicePurchases12312016.csv`: Purchase invoices.
- `PurchasesFINAL12312016.csv`: Purchase details.
- `SalesFINAL12312016.csv`: Sales transactions.

These files are assumed to be uploaded to `MyDrive/slooze_dataset` in Google Drive for Colab access.

## Requirements
- **Platform**: Google Colab (recommended) or Jupyter Notebook.
- **Libraries**:
  ```bash
  pip install pandas numpy matplotlib seaborn prophet
