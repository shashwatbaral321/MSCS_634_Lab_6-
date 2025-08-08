# Lab 6: Association Rule Mining Utilizing Apriori and FP-Growth
**Name:** Shashwat Baral  
**Course:** MSCS-634-B01 – Advanced Big Data and Data Mining  
**Date:** August 2025  

## Purpose
The objective of this lab was to investigate association rule mining methodologies through the application of the **Apriori** and **FP-Growth** algorithms on actual transactional data. The aim was to discover frequent itemsets, create association rules, and analyze patterns that could aid in business decision-making.

## Key Insights
- **Most Frequently Purchased Items:** The "White Hanging Heart T-Light Holder" and the "Regency Cakestand 3 Tier" emerged as the top purchases within the dataset.
- **Significant Associations:** Products associated with kitchen and home décor frequently appeared together in transactions.
- **Performance of Algorithms:** The FP-Growth algorithm yielded the same frequent itemsets as the Apriori method but demonstrated a significantly faster processing time for the dataset in question.
- **Strength of Rules:** Rules exhibiting high lift values suggested strong affinities between products, which can be advantageous for cross-selling initiatives.

## Challenges & Decisions
- **Data Cleaning Process:** The dataset contained missing `CustomerID` entries and negative quantities, necessitating their removal to prevent skewed results.
- **Support Threshold Selection:** A support threshold of `0.02` was established to strike a balance between an excessive number of trivial rules and a scarcity of significant patterns.
- **Choice of Algorithm:** Both algorithms were utilized for comparative analysis; however, FP-Growth was favored for larger datasets due to its superior efficiency.

## Tools & Libraries
- **Python**, **Pandas**, **Seaborn**, **Matplotlib**
- **mlxtend** for the implementation of Apriori, FP-Growth, and the generation of association rules.
