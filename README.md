Song Success Prediction Model

Author: Cameron Hicks

Project Overview

The objective of this project was to determine whether a song’s pre-release attributes could be used to predict its commercial success on Spotify. Specifically, this project aimed to build a regression model capable of predicting Spotify’s popularity score using only features available prior to or at release time.

The intended use case for this model was to provide artists, labels, and decision makers with an analytical tool to evaluate projected song performance before investing in marketing and promotion.

After extensive data preparation, exploratory analysis, modeling, and baseline comparison, the final determination is that the available dataset does not contain sufficient predictive signal to build a model that meaningfully outperforms a naïve baseline predictor.

Key Findings

No regression model (Linear Regression, Random Forest, Gradient Boosting) outperformed a Dummy baseline model.

All models produced near-zero or negative R² values.

MAE and RMSE were nearly identical across trained models and baseline models.

Audio and descriptive metadata alone are insufficient to explain variation in song popularity.

Song success is likely driven by external factors not present in the dataset (marketing, playlist placement, artist reputation, timing, etc.).

This negative result is supported by rigorous baseline comparison and is fully documented in the project report.

Repository Structure
- Data
    - Source CSV files
    - Cleaned and merged datasets
- Notebooks
        - Data_Wrangling.ipynb
        - EDA.ipynb
        - Preprocessing.ipynb
        - Modeling.ipynb
    - Alternatives
        - V2 – Hit Classification notebooks
        - V3 – Country Prediction notebooks
    - outputs
        - model_metrics.json
- Project Proposal
    - Project_Proposal.pdf
- Project Report
    - Song Success Prediction Model Final Project Report by Cameron Hicks.pdf
