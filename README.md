**E-Commerce-Recommendations**
Recommendation System for E-Commerce Project (Python)
Analysis with SQLite using Pandas


**Methods Used**
Data Analysis with SQLite and Pandas
Market Basket Analysis
Apriori Algorithm
Association Rule Mining
Technologies/Libraries Used
Python 3
SQLite3
Pandas
NumPy
mlxtend
Jupyter

**Description**
The premise of this project is a hypothetical company, "The Company", in the e-commerce industry that would like to develop a recommendation system. "The Company" specializes in selling adhesives and sealants in addition to many related products in other categories.

**There are two parts:**

Notebook: Includes code and brief EDA for technical departments. Uses transaction data from "The Company" to show how to identify complementary products using machine learning techniques to lay the foundation for an automated recommendation engine.
PowerPoint: Presents findings for business stakeholders. Discusses when brands matter and why customers may choose one brand over another. Then presents how to automatically detect items to use in recommendation system with examples from findings developed in the notebook.
Data
The data used will be two datasets that have been combined. There is a dataset with six months of transactions where items in the "adhesives and sealants" category were purchased and another dataset containing all transactions over a two week period. The raw data contains:

Order Number: The unique identifier for each individual transaction
l1: Level 1 product identifier (most broad)
l2: Level 2 product identifier
l3: Level 3 product identifier (most granular)
Sku: The unique identifier for a specific item
Brand: The unique identifier for the specific brand of an item

**Summary**
The apriori algorithm and association rule mining were used to extract frequent itemsets (items purchased together) from the data and generate rules for frequent item patterns. These rules can be used in a recommendation engine in the context of "customers who viewed ... also viewed..." and "customers who purchased ... also purchased..." in order to encourage add-on purchases or encourage past customers to continue using "The Company" for their e-commerce needs. The results are contained in a CSV file that can be used across platforms for production purposes.
