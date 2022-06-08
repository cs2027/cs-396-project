# Descriptions of Various Files

## Code Files

### `project_proposal.ipynb`

* Code associated with initial project proposal
* Includes data cleaning steps, EDA

### `milestone.ipynb`

* Includes some basic models without much tuning / analysis (for intermediate milestone)
* Models used include KNN, logistic regression, ensemble methods (gradient boosting, AdaBoost, random forest, extra trees)

### `knn-and-lr.ipynb`

* Model tuning for KNN, logistic regression models (for final project)

### `ensemble-models.ipynb`

* Model tuning for more advanced ensemble methods - gradient boosting, AdaBoost, random forest, extra trees - for final project

## Data Files

### `heart_2020_cleaned.csv`

* Original dataset with over 300,000 entires

### `heart_2020_cleaned_v2.csv`

* Reduced / sampled dataset with 20,000 entries (see `Data Cleaning` section in project report for more details)
* This was the dataset used for the train / test split for model building purposes, although due to undersampling, many of these (20,000) entries were not used due to the strong imbalance of response variable in our dataset
