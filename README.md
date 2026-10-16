# Supermarket Customer Satisfaction: Data Mining

Cleaning and exploratory analysis of a 5,000-response supermarket customer-survey dataset (23 columns: demographics, shopping behaviour, basket composition, satisfaction rating and free-text comments).

## What the notebook does (`notebooks/Data_Mining.ipynb`)

1. Loads the data and documents each column.
2. Assesses data quality: missing values (comments, distance to store, payment method, income), numeric and categorical summaries.
3. Visualises outliers with boxplots.
4. Cleans: clips implausible ages, fixes misspelled store locations and shopping-mission labels.
5. Engineers features such as total items bought and age group.
6. Explores satisfaction by shopping mission, age group, loyalty card, time in store and basket size.

Figures from each stage are in `figures/`.

## Next steps

Modelling satisfaction (classification) and text analysis of the free-text comments are not done yet.

---
**Author:** Mohsin Hassan · [GitHub](https://github.com/MohsinHassan-8) · [LinkedIn](https://linkedin.com/in/mohsin-hassan-gen-ai)
