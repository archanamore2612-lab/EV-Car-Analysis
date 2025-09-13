# EV-Car-Analysis

Data-driven analysis of Electric Vehicle specifications (FEV) with Python. Includes data cleaning, feature engineering, EDA, visual insights, and key performance trends to understand battery range, efficiency, pricing, and brand-wise performance.

## Dataset Overview

-**Source:**  - 'FEV-data-Excel.xlsx'
-**Total Columns:** 25
-**Topics Covered:** Price, Range, Battery Capacity, Power, Torque, Weight, Speed, Brand, Charging Capability

## 🎯 Project Objectives

- Clean and standardize raw EV specifications  
- Create informative engineered features  
- Perform basic and advanced exploratory data analysis  
- Visualize key trends across price, brand, and performance  
- Identify outliers and top performers in efficiency and value  
- Extract insights for potential buyers, manufacturers, or investors
 
## Feature Engineering Highlights

| Feature Nam          | Description                                |
|----------------------|--------------------------------------------|
| power_to_weight      | Engine power divided by vehicle weight     |
| km_per_kwh           | Efficiency: Range per unit battery         |
| price_per_km         | Cost per km of range                       |
| battery_power_product| Interaction feature of battery × power     |
| log_price            | Log-transformed price to reduce skewness   |
| price_bin            | Categorical price segmentation (Low–High)  |
| range_bin            | Categorical range segmentation             |

## Key Visualizations

- Price vs Range scatterplots
- KDE distributions of efficiency
- Correlation heatmaps
- Average range and price per brand
- Boxplots of new features
- Top 5 efficient or overpriced models

## Technologies Used
- **Python**
- **Pandas** & **NumPy** – data preprocessing
- **Matplotlib** & **Seaborn** – visualization
- **Jupyter Notebook** – development environment
