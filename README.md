# Project: Predict S&P Stock Market Prices Using Machine Learning and Python
## Ana Matavulj

## Table of Contents
<ul>
<li><a href="#getting-started">Getting Started</a></li>
<li><a href="#intro">Introduction</a></li>
<li><a href="#summary">Summary</a></li>
</ul>

<a id='getting-started'></a>

## Getting Started

This project requires Python, JupyterLab, and the following Python libraries:

- [pandas](http://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org)
- [yfinance](https://pypi.org/project/yfinance/)


### Run
In a terminal or command window, run the following command:

    jupyter lab
    
This will open the Jupyter Lab software in your browser and you can navigate to the directory where the file is.

<a id='intro'></a>

## Introduction

This project predicts tomorrow's S&P 500 index price using historical data from the 1990s to today. A nice chart of S&P 500 price history is downloaded through the yfinance module in Python. The goal of this model is to predict whether stock goes up or down from today. 

<a id='summary'></a>
## Summary

The S&P 500 index's columns (open, close, high, low, etc) are used to predict whether the stock price will rise or fall. Data cleaning and deleting columns that are more appropriate for individual stocks is essential to a more efficient model. Using the RandomForestClassifier allows nonlinear relationships within the market to be identified, which is key since most of the stock market is nonlinear. My original model was not precise, however I built a backtesting system and added predictors to suffiently increase the precision of my model. 
