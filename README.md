# Association Analysis Repo

This repo contains code for an assosiation analysis mini project. Replicating http://pbpython.com/market-basket-analysis.html


## Prerequisites

1. Data : http://archive.ics.uci.edu/ml/datasets/Online+Retail

2. Library : Mlxtend

3. Python version : 3.6.4 (you can use older version)


## Flow
1. Data cleaning: Clean data by removing missing values , removing credit invoices.
2. Data Preperation : The model need to take the data represetnted in 1 record per invoice and all related products in the same record. This is represented using hot encoding method where the products are turn into columns and the value 1/0 represent it's appearance or not.
3. Model: We use Apriori Algorithm to  calculate assosiation between rules.

## Results
1. Confidence :freq(x,y)/freq(x)
2. Support: freq(x,y)/N
3. Lift: support/(supp(x)*supp(y))












