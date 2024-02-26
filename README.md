# Bulldozer Price Prediction Project

This repository contains all the materials and code for the Bulldozer Price Prediction project, which is based on the "Blue Book for Bulldozers" Kaggle competition. The goal of this project is to predict the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers.

## Project Overview

The data for this competition is split into three parts:

- **Train.csv**: Training set, which contains data through the end of 2011.
- **Valid.csv**: Validation set, which contains data from January 1, 2012, to April 30, 2012. You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
- **Test.csv**: Test set, which contains data from May 1, 2012, to November 2012. The test set is used for your final submissions.

The key metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

## Repository Structure

- `notebooks`: This directory contains Jupyter notebooks used for exploratory data analysis, model development, and evaluation.
- `data`: Directory containing the dataset. Note: due to GitHub's file size limit, It is recommended downloading the dataset directly from the Kaggle competition page.
- `models`: Trained models are saved here.


## Model

The project uses a `RandomForestRegressor` from the scikit-learn library, optimized through hyperparameter tuning. The final model parameters were determined after extensive experimentation and validation.

## Results

The model achieved an RMSLE of 0.24397961163746332 on the validation set and Y.YYY (true values are with kaggle and tested only upon submission to prevent overfitting to get better test scores) on the test set. These results demonstrate the effectiveness of the chosen approach and the potential for further refinement.
