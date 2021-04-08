# Hybrid Recommendation System

## Summary

In this repository an example code is presented on how to put a `LightFM` hybrid recommendation
system into production.

The `MovieLens` dataset is used to train a `LightFM` model. Then it is illustrated how to quickly
incorporate new interactions to the model, without completely retraining it, using the
`fit_partial` function. Finally, it is showed how to prepare the model to anticipate new
users / items, by padding the training data with some dummy users / items.

## Getting Started

Create a Python 3 environment and install the dependencies from `requirements.txt`.
Open the `recommendation_to_production.ipynb` notebook.
