# Seasonal Agriculture Performance Analysis

EDA project analyzing how agricultural performance varies across India's three cropping seasons, Kharif, Rabi, and Zaid, using a dataset of 4,000 farm-level records across 8 states and 8 crops.

## Key Finding

Zaid season shows a negative average profit across the dataset, but this is misleading at face value. The loss is driven almost entirely by staple grain crops (Rice, Wheat, Maize, Pulses), which are already thin margin or loss making in every season and simply worsen under Zaid's added heat and water stress. High value crops like Chilli and Sugarcane stay profitable across all three seasons, including Zaid. Environmental variables (rainfall, temperature, soil moisture, disease and pest risk) show near zero correlation with yield, meaning crop choice explains far more variation than season or environment in this dataset.

## What's Inside

- Data cleaning with season and crop aware median imputation for missing values
- Outlier sanity checks (e.g. confirming Sugarcane's high yield values are legitimate, not errors)
- Profitability analysis across seasons and crops
- Regional breakdown of Zaid season performance across states
- Correlation analysis of yield drivers (environmental vs. crop and resource related)
- Kruskal-Wallis significance testing on yield and profit across seasons (non-parametric, since the data is skewed)
- Irrigation strategy comparison across seasons
- Insights and recommendations for agricultural planning

## Tools

Python, pandas, matplotlib, seaborn, scipy

## Dataset

4,000 records, 28 features covering environmental conditions, resource usage, and economic outcomes, spanning Kharif, Rabi, and Zaid seasons across 8 Indian states and 8 crops.

## Done By

Acsah Pauline K
