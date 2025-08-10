# ​ Association Rules Analysis – Market Basket

## Overview
This project utilizes the **Apriori algorithm** to analyze a grocery transaction dataset and discover frequent itemsets. By generating **association rules**, it uncovers which products are frequently purchased together—empowering data-driven merchandising and cross-selling strategies.

## Dataset
- **File**: `groceries - groceries.csv`
- Format: Each row represents a customer transaction consisting of multiple purchased items.

## Tech Stack
- **Python**
- **Pandas** – Data processing
- **Mlxtend** – Market basket analysis (Apriori & association_rules)

## How to Run
```bash
git clone https://github.com/JaydenMirr1173/association-rules-market-basket.git
cd association-rules-market-basket/Association-Rules-Analysis
pip install pandas mlxtend
jupyter notebook ASSOCIATION_RULES_GROCERIES.ipynb
