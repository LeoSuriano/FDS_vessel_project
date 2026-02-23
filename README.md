# Vessel-Type Classification from AIS Data

This repository contains a small supervised learning project to classify **vessel types** using **ship-level features** extracted from **NOAA AIS data**.

## What’s inside
- A notebook that loads a cleaned dataset, preprocesses features (imputation + scaling), trains a neural network, and evaluates results.
- A short report with the project description and findings.

## Main idea
AIS vessel type labels can be missing or unreliable. The goal is to train a model that predicts a vessel’s macro-class (e.g. Cargo, Tanker, Passenger and so on) from basic geometry and movement-related features.

