# AI Programming Foundations Project

## Project Description

This project analyzes the Titanic dataset using a reproducible Python data workflow. The workflow includes data loading, data inspection, data cleaning, exploratory data analysis, visualizations, and a short interpretation of the results.

## GitHub Repository

Repository link: https://github.com/GierlStefan/ai-programming-foundations-project

## Dataset

Dataset used: Titanic - Machine Learning from Disaster

Source: https://www.kaggle.com/c/titanic

The main dataset file used in this project is:

- train.csv

## What Was Built

This project includes:

- A Jupyter Notebook named data_workflow.ipynb
- Data loading with Pandas
- Data cleaning functions with docstrings
- Exploratory data analysis
- Three visualizations with interpretations
- A summary and interpretation section
- A requirements.txt file for reproducibility
- A module_summary.pdf report with academic citations

## How to Install Dependencies

Run this command in the project folder:

pip install -r requirements.txt

## How to Run the Project

Start Jupyter Notebook with this command:

jupyter notebook

Then open:

data_workflow.ipynb

Run all cells from top to bottom.

## Reproducibility

The project can be reproduced by using the included requirements.txt file and running the notebook in order. The notebook is structured into clear sections for setup, data ingestion, cleaning, exploratory analysis, visualizations, and summary.

The project also uses Git and GitHub for version control. The repository includes multiple commits and an additional development branch beyond main.

## Bias Awareness and Data Quality

Poor data cleaning can introduce bias or misleading results. In this project, missing Age values were filled with the median age. This keeps the dataset complete, but it may reduce the natural variation in passenger ages. As a result, age-based conclusions should be interpreted carefully.

The Cabin column was removed because it had many missing values. This was reasonable for a simple workflow, but it also means that possible information about passenger location on the ship was not analyzed. Passenger location may have influenced survival chances, so removing Cabin could hide an important historical factor.

The dataset also reflects only the available Titanic passenger data. It should not be interpreted as a complete explanation of every individual survival outcome. The analysis shows general patterns, not guaranteed causal relationships.

## Future Integration Reflections

This workflow could support a future machine learning project. The current cleaning functions, feature engineering steps, and exploratory analysis could be reused before training models such as logistic regression, decision trees, or random forests.

For a neural network workflow, the dataset would need additional preparation. Categorical variables such as Sex and Embarked would need to be encoded numerically. Numeric variables such as Age and Fare would likely need scaling. The data would also need to be split into training, validation, and test sets.

Agentic automation could also improve this workflow in the future. An AI agent could help detect missing values, suggest cleaning steps, generate standard EDA summaries, create visualizations, and check whether the notebook runs without errors. However, human review would still be important to avoid incorrect assumptions or misleading automated decisions.

## Files Included

- data_workflow.ipynb
- README.md
- requirements.txt
- module_summary.pdf
- train.csv
- test.csv
- gender_submission.csv
