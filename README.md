# UYIK2024_Counterfactual_Explanations_of_Bank_Failure_Prediction_Models

This repository contains code and resources for implementing counterfactual explanations for bank failure prediction models.

## Table of Contents

1. [Overview](#overview)
2. [Contents](#contents)
3. [Getting Started](#getting-started)

## Overview <a name="overview"></a>

Bank failure prediction is a vital component of financial risk management. Predictive models are developed to estimate the probability of a bank failing by analyzing various characteristics and historical data. However, stakeholders such as regulators, investors and bank management must understand the underlying reasons for these model predictions.

Counterfactual explanations offer valuable insights into the reasoning behind a particular forecast by identifying the minimum changes needed to alter the forecast outcome. In predicting bank failures, these explanations can enlighten the factors driving the model's decisions and allow stakeholders to take proactive measures to manage and minimize potential risks.

## Contents <a name="contents"></a>

- `data/`: This directory contains datasets used for training and evaluation.
- `model/`: Implementation of bank failure prediction models.
- `counterfactual_for_all_models/`: Codes for generating counterfactual explanations.
- `activeData.Rda`: R data file containing active data.
- `failureData.Rda`: R data file containing failure data.
- `libraries.R`: Script for loading required libraries.


## Getting Started  <a name="getting-started"></a>

1. Clone this repository to your local machine.
2. Install the required packages listed in [libraries.R](https://github.com/seymagnn/UYIK2024_Counterfactual_Explanations_of_Bank_Failure_Prediction_Models/blob/main/libraries.R) script.
3. Complete data manipulation operations by pulling metrics from the [arranging_data.R](https://github.com/seymagnn/UYIK2024_Counterfactual_Explanations_of_Bank_Failure_Prediction_Models/blob/main/data/arranging_data.R) script.
4. Splitting data into two subsets in [model_partition.R](https://github.com/seymagnn/UYIK2024_Counterfactual_Explanations_of_Bank_Failure_Prediction_Models/blob/main/model/model_partition.R) script.
5. Each model is included in a weighting method. You can get all the counterfactuals which are generated in [Weighting](https://github.com/seymagnn/UYIK2024_Counterfactual_Explanations_of_Bank_Failure_Prediction_Models/tree/main/counterfactuals_for_all_models/weighting) scripts.
