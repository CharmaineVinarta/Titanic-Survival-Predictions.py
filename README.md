# Titanic-Survival-Predictions.py

# Titanic Kaggle Competition

This repository is for the legendary Titanic Machine Learning competition on Kaggle. It's a great first challenge to get started with ML competitions and familiarize myself with the Kaggle platform.

## Description

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the widely considered "unsinkable" RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren't enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

In this challenge, I was tasked with building a predictive model that answers the question: "What sorts of people were more likely to survive?" using passenger data (i.e., name, age, gender, socio-economic class, etc).

## Data

In this competition, I gained access to two similar datasets that include passenger information like name, age, gender, socio-economic class, etc. One dataset is titled `train.csv` and the other is titled `test.csv`.

`train.csv` will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the "ground truth."

The `test.csv` dataset contains similar information but does not disclose the "ground truth" for each passenger. It's my job to predict these outcomes.

Using the patterns I find in the `train.csv` data, predict whether the other 418 passengers on board (found in `test.csv`) survived.
