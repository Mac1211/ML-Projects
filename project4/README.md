# Overview:

This repository contains Python code for implementing Thompson Sampling algorithm to solve the Multi-Armed Bandit Problem. The Multi-Armed Bandit Problem is a classic problem in probability theory and decision theory where an agent seeks to maximize cumulative reward while faced with a sequence of decisions, each of which has uncertain outcomes and different reward probabilities. The dataset used in this project is Ads_CTR_Optimisation.csv. It represents a simulation of online advertisement click-through rates (CTR) for different ads. The dependencies are numpy, Matplolib, pandas.
# Contents:

1. thompson_sampling.py: Python script for implementing Thompson Sampling algorithm for the Multi-Armed Bandit Problem.
2. Ads_CTR_Optimisation.csv: Dataset containing simulated advertisement click-through rates.
3. README.md: This file providing an overview of the project.
# Result:

The script outputs a histogram visualizing the number of times each ad was selected based on the Thompson Sampling algorithm. This helps in understanding which ads are more likely to be clicked based on the historical data.