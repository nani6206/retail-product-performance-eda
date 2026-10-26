# Retail Product Performance EDA

**Author:** Maganti Nagarjuna  
**Project type:** Exploratory Data Analysis (EDA)  
**Analysis period:** January–June 2026

## Overview

This project analyzes retail transaction data across five product categories to help a category manager evaluate revenue trends, product performance, discount effectiveness, and promotional timing.

## Questions explored

- What does the dataset contain, and are there data-quality issues?
- Which categories are growing, declining, or relatively consistent over time?
- Which two products are the highest and lowest performers by revenue in each category?
- How do average transaction revenue and units sold vary by discount bracket?
- How do revenue patterns vary by weekday and month?
- What actions and additional data should be considered before supplier discussions?

## Key findings

- Electronics revenue decreased by approximately 35% from January to June 2026.
- Apparel revenue increased by approximately 34% over the same period.
- Grocery was comparatively consistent across the six-month period.
- Average revenue per transaction did not increase proportionately at higher observed discount levels; this is an association, not proof of causation.
- The dataset contains no cost or margin field, so profitability and margin erosion cannot be measured directly.
- The data has no transactions in the 25%+ discount bracket; discount conclusions apply only to observed levels up to 20%.

## Repository contents

- `InsightForge_MUC01_DIET_Notebook.ipynb` — analysis, charts, interpretations, and recommendations.
- `MUC01_Retail_Sales_Dataset.csv` — source dataset used by the notebook.
- `requirements.txt` — Python dependencies.

## Run locally

1. Clone or download this repository.
2. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Open the notebook in Jupyter:

   ```bash
   jupyter notebook InsightForge_MUC01_DIET_Notebook.ipynb
   ```

4. Keep the CSV in the same directory as the notebook and run all cells from top to bottom.

## Limitations

The dataset covers only six months and does not include product costs, margins, stock-outs, supplier identifiers, or customer-level details. Seasonal effects, promotions, and inventory availability cannot be separated reliably. Recommendations should therefore be treated as evidence-based starting points and revisited when additional data is available.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.
