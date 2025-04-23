# IS362 – Week 12 Assignment: Preprocessing Data for Scikit-learn  
**BY:** Daniela Porras

## Overview  
This notebook is part of the Week 12 assignment for IS362. The goal was to preprocess a dataset to prepare it for future predictive modeling using scikit-learn in Project 4. I used the well-known Mushroom dataset from the UCI Machine Learning Repository, which contains various attributes of mushrooms and whether they are edible or poisonous.

## Objectives  
- Load the Mushroom dataset and assign meaningful column names  
- Select a subset of features:  
  - `class` (edible or poisonous) – target variable  
  - `odor` – potentially strong predictor  
  - `gill-color` – additional feature for pattern discovery  
- Rename the selected columns for clarity  
- Convert all categorical values to numeric using mapping  
- Perform exploratory data analysis (EDA) with histograms and scatterplots  
- Draw preliminary conclusions about which features may be most useful in predicting mushroom edibility

## Technologies Used  
- Python  
- pandas  
- matplotlib  
- seaborn  
- Jupyter Notebook  

## Files Included  
- `agaricus-lepiota.data` – Mushroom dataset from UCI  
- `Week12_Mushroom_EDA.ipynb` – Main Jupyter Notebook (assignment deliverable)  
- `README.md` – This file

## Key Insights  
- The `odor` feature appears to be a very strong predictor of whether a mushroom is poisonous.  
- The `gill_color` feature has more overlap but may still provide value in a combined model.  
- Data was successfully transformed into numeric format for use in downstream analysis with scikit-learn.

## Data Source  
Mushroom Dataset:  
https://archive.ics.uci.edu/ml/datasets/Mushroom

## License  
This project is for academic use only as part of coursework at CUNY School of Professional Studies.
