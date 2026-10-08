# Customer Segmentation using RFM Analysis and KMeans Clustering

Segments online retail customers using RFM analysis (Recency, Frequency, Monetary value) and KMeans clustering in Python, so a business can target marketing, retention, and loyalty efforts at the right groups.

## What this project does

1. Loads and cleans the online retail transaction data with pandas
2. Builds RFM features for each customer
   - **Recency:** days since the last purchase
   - **Frequency:** number of purchases
   - **Monetary value:** total amount spent
3. Separates extreme outliers (high monetary value and/or high frequency) into their own groups
4. Clusters the remaining customers with KMeans (scikit-learn)
5. Labels each cluster with a business-friendly name and visualizes the results

## Customer segments

| Cluster | Label | Group |
|:-------:|-------|-------|
| 0 | Retain | Regular customers |
| 1 | Re-engage | Regular customers |
| 2 | Nurture | Regular customers |
| 3 | Reward | Regular customers |
| -1 | Pamper | Outliers: high monetary value only |
| -2 | Upsell | Outliers: high frequency only |
| -3 | Delight | Outliers: high monetary value and high frequency |

## Tech stack

Python, pandas, scikit-learn, matplotlib, seaborn, openpyxl, Jupyter Notebook


## Dataset

Online Retail Dataset : https://archive.ics.uci.edu/dataset/502/online+retail+ii

## Author

Renu Mahato | [GitHub](https://github.com/RenuMahato) | [LinkedIn](www.linkedin.com/in/renu-kumari-84414a387)

