# Customer Segmentation with KMeans

This project analyzes customer purchasing behavior using KMeans clustering on a retail dataset. The analysis segments customers into actionable groups based on Recency, Frequency, and Monetary value (RFM), enabling data-driven marketing and retention strategies.

## Features

- **Data Cleaning:** Handles missing values, invalid entries, and outliers.
- **Feature Engineering:** Computes RFM features for each customer.
- **Outlier Analysis:** Separates and analyzes high-value and high-frequency outliers.
- **Clustering:** Applies KMeans to segment customers.
- **Visualization:** 2D/3D plots and violin plots for cluster interpretation.
- **Actionable Insights:** Maps clusters to business strategies (e.g., Retain, Reward, Upsell).

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Place `online_retail_ii.zip` in the project directory.
2. Run the notebook:
   - Open `customer_kmeans_analysis.ipynb` in Jupyter or VS Code.
   - Execute cells sequentially.

## Project Structure

- `customer_kmeans_analysis.ipynb` — Main analysis notebook.
- `online_retail_ii.zip` — Dataset (not included, download from UCI repository).

## Cluster Interpretation

- **Re-Engage:** Low value, infrequent, old customers.
- **Retain:** High value, frequent, not recent.
- **Reward:** High value, frequent, recent.
- **Nurture:** Low value, least active, recent.
- **Pamper/Upsell/Delight:** Outlier groups for special strategies.

## License

For educational use only.

---
