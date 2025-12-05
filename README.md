# Chess Winner Prediction

## Project Overview
This project applies machine learning techniques to predict the winner of online chess games (White vs. Black) using data from Lichess.org. By analyzing over 20,000 games, we attempt to determine how much pre-game factors like ELO rating and time controls influence the final result.

## Structure
* `data/`: Contains the raw dataset.
* `notebooks/`:
    * `01_eda.ipynb`: Exploratory Data Analysis and Feature Engineering.
    * `02_modeling.ipynb`: Model training (Logistic Regression & Random Forest) and evaluation.
* `reports/`: Contains the final write-up and presentation.

## Key Findings
* **Rating Difference** is the single strongest predictor of victory.
* The **Random Forest** model achieved the highest accuracy, outperforming the baseline and Logistic Regression.
