# Market-Basket-Analysis

# Project Architecture

A[Groceries Dataset (.csv)] --> B[Google Colab]

B --> C[Data Inspection]

C --> D[Missing Value Analysis]

D --> E[Data Preparation]

E --> F[Apriori Algorithm]

F --> G[Frequent Itemsets]

G --> H[Association Rules]

H --> I[Support]

H --> J[Confidence]

H --> K[Lift]

I --> L[Rule Ranking]

J --> L

K --> L

L --> M[Visualizations]

M --> N[Business Insights]

# Project Purpose
Market Basket Analysis is a data mining technique used to identify products that are frequently purchased together. Retailers and e-commerce businesses use these insights to optimise product placement, create effective promotional bundles, improve recommendation systems, and increase cross-selling opportunities.

This project applies the Apriori Algorithm to a grocery transaction dataset to discover meaningful product associations using support, confidence, and lift metrics. The results are further analysed through visualisations to provide actionable business insights.

# Project Overview
This project performs Market Basket Analysis using a grocery transaction dataset.

The dataset is imported into Google Colab, where it is first inspected to understand its structure and verify data quality. Missing values are checked before preparing the transaction data for association rule mining.

The Apriori algorithm is then applied to identify frequent itemsets based on minimum support thresholds. From these frequent itemsets, association rules are generated and evaluated based on support, confidence, and lift.

The generated rules are ranked according to confidence and support to identify the strongest product relationships. Finally, several visualisations are created to present these associations intuitively, with descriptions explaining the significance of each chart and its resulting business implications.

# Project Workflow
Dataset Collection > Import Dataset > Dataset Inspection > Missing Value Analysis > Transaction Preparation > Apriori Algorithm > Frequent Itemset Mining > Association Rule Generation > Support • Confidence • Lift > Rule Ranking > Visualizations > Business Insights

# Analysis Performed
Imported grocery transaction dataset.
Inspected dataset structure.
Verified missing values.
Applied the Apriori Algorithm.
Generated frequent itemsets.
Calculated support values.
Generated association rules.
Evaluated rules using confidence and lift.
Ranked association rules based on support and confidence.
Created visualisations to interpret purchasing behaviour.
Derived business recommendations for cross-selling.

# Business Insights
The analysis can help businesses:

Discover products that customers frequently purchase together.
Create attractive product bundles.
Improve product recommendations.
Optimise shelf placement in retail stores.
Increase cross-selling opportunities.
Design targeted promotional campaigns.
Improve inventory planning based on purchasing patterns.

# Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
mlxtend
Apriori Algorithm
Association Rule Mining

# Repository Structure
Market-Basket-Analysis/
│
├── groceries_dataset.csv
├── Market_Basket_Analysis.ipynb
├── images/
│   ├── chart_1.png
│   ├── chart_2.png
│   ├── chart_3.png
│   └── chart_4.png
└── README.md
