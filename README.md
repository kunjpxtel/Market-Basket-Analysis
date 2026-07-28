# Market-Basket-Analysis

# Project Purpose
Market Basket Analysis is a data mining technique used to identify products that are frequently purchased together. Retailers and e-commerce businesses use these insights to optimise product placement, create effective promotional bundles, improve recommendation systems, and increase cross-selling opportunities.

This project applies the Apriori Algorithm to a grocery transaction dataset to discover meaningful product associations using support, confidence, and lift metrics. The results are further analysed through visualisations to provide actionable business insights.

# Project Overview
This project performs Market Basket Analysis using a grocery transaction dataset.

The dataset is imported into Google Colab, where it is first inspected to understand its structure and verify data quality. Missing values are checked before preparing the transaction data for association rule mining.

The Apriori algorithm is then applied to identify frequent itemsets based on minimum support thresholds. From these frequent itemsets, association rules are generated and evaluated based on support, confidence, and lift.

The generated rules are ranked according to confidence and support to identify the strongest product relationships. Finally, several visualisations are created to present these associations intuitively, with descriptions explaining the significance of each chart and its resulting business implications.

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

# Visualizations
<table>
  <!-- Row 1 -->
  <tr>
    <td>
      <img src="Image/Association%20Rules%20Confidence%20vs.%20Support.png" alt="Confidence vs. Support" width="450" height="320" style="object-fit: cover;">
    </td>
    <td>
      <img src="Image/Top%2015%20Rules:%20Parallel%20Item%20Coordinates%20Pathway.png" alt="Parallel Item Coordinates" width="450" height="320" style="object-fit: cover;">
    </td>
  </tr>
  
  <!-- Row 2 -->
  <tr>
    <td>
      <img src="Image/Association%20Rules%20Confidence%20Heatmap.png" alt="Confidence Heatmap" width="450" height="320" style="object-fit: cover;">
    </td>
    <td>
      <img src="Image/Network%20Graph%20of%20Top%20Association%20Rules%20%28Lift-based%20Product%20Clusters%29.png" alt="Network Graph" width="450" height="320" style="object-fit: cover;">
    </td>
  </tr>

  <!-- Row 3 -->
  <tr>
    <td>
      <img src="Image/Top%2015%20Association%20Rules%20by%20Confidence.png" alt="Top 15 Rules by Confidence" width="450" height="320" style="object-fit: cover;">
    </td>
    <td>
      <img src="Image/Top%2010%20Association%20Rules%20-%20Multi-Metric%20Comparison.png" alt="Top 10 Multi-Metric" width="450" height="320" style="object-fit: cover;">
    </td>
  </tr>
</table>



# Technologies Used
Python,
Google Colab,
Pandas,
NumPy,
Matplotlib,
mlxtend,
Apriori Algorithm,
and Association Rule Mining

# Repository Structure
Market-Basket-Analysis/

Groceries_dataset.csv, Market_Basket_Analysis.ipynb, Images and README.md

# How to Use
1. Clone the Repository
git clone https://github.com/kunjpxtel/Market-Basket-Analysis.git

3. Open the Analysis Files

The repository contains:

Original Grocery Transactions Dataset (groceries_dataset.csv)
Processed/Analyzed Dataset (analyzed_data.csv)
Google Colab/Jupyter Notebook (.ipynb) containing the complete Market Basket Analysis workflow

These files can be explored using:

Google Colab
Jupyter Notebook
Microsoft Excel
Python (Pandas)

3. Run the Analysis

Open the notebook in Google Colab or Jupyter Notebook, then execute all cells sequentially to:

Load the transaction dataset
Inspect the dataset and check for missing values
Prepare the transaction data
Generate frequent itemsets using the Apriori algorithm
Create association rules
Calculate support, confidence, and lift
Rank rules based on confidence and support
Generate visualisations and business insights

4. View the Analysis Results

The repository includes visualisations illustrating:

Frequent Itemsets
Association Rules
Support Analysis
Confidence Analysis
Lift Analysis

Review the generated charts and their accompanying descriptions to understand customer purchasing patterns and product associations.




