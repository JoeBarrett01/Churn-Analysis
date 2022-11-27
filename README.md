# Churn Analysis

The following provides an analysis of churn - objectively identifying key features that may impact Oracle Cloud Infrastructure Churn.

1.	Are there unstudied or uncalculated characteristics that might impact the probability of a startup churning?
2.	Do we need to adjust our definition of churn (e.g., no usage for 15 days or adding an additional condition)?

## Overview

1. Customer churn is the percentage of customers that stop using a product. For most services, the definition is straightforward: in most industries, it means that the customer stops using. Our current definition is startups that started consuming OCI (>$0 total consumption), and then had 30 days or more of $0 usage. You and the other analysts began to answer this question, so your work would deepen the question.

2. I aim to answer the following
- Are there unstudied or uncalculated characteristics that might impact the probability of a startup churning?
- Does Oracle need to adjust the definition of churn (e.g., no usage for 15 days or adding an additional condition)?

## Oracle Cloud Consumption 
1. Can we predict how much a startup will consume based on their characteristics?

## Results
- [Data Science Rotation.pdf](https://github.com/JoeBarrett01/Churn-Analysis/files/10098623/Data.Science.Rotation.pdf)

## Logistics
- Google Colaboratory will be used, analysis accross R and python. Code is written in the most general form such that the final_decision_tree.ipynb must mount your Drive, rather than proceed with SSH for easiest use. 

