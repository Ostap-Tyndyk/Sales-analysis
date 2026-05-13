# Global Sales EDA

Exploratory data analysis of global sales data (2010–2017, 1328 orders, 45 countries) using CSV files + Python.

## Data Sources

Three CSV files joined into one dataset: `events.csv` (orders) · `products.csv` (categories) · `countries.csv` (regions)

## What's Analyzed

- **Categories** — revenue, cost, profit, units sold by product type
- **Geography** — top countries, regions, sub-regions by all key metrics
- **Sales channel** — Online vs Offline comparison
- **Delivery** — avg delivery time by category, country, region; correlation with profit
- **Dynamics** — profit trends by year (category, country, region) and by weekday

## Key Findings

- Total profit: **$501M** across 45 countries
- Top category by profit: **Cosmetics**; top by units sold: **Clothes & Office Supplies**
- **Europe** (especially Eastern) dominates; Asia is nearly untapped
- Online and Offline channels are nearly equal across all metrics
- Delivery time (0–50 days) has no impact on profit

## Requirements

Google Colab with Google Drive · `pandas` · `matplotlib` · `seaborn`
