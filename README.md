# Corporate Share Repurchase Prediction

A machine learning research project examining corporate share
repurchase prediction and its application to stock selection.

## Research paper

[Read the research paper](reports/research_paper.pdf)

## Project workflow

1. Build the financial dataset and buyback labels.
2. Clean the dataset and engineer features.
3. Explore the data.
4. Train and compare classification models.
5. Evaluate predictions in stock-selection strategies.

The five notebooks are in the notebooks folder, numbered in
workflow order.

## Data

Financial data were collected through StockAInsights.
Large financial datasets and generated model files are not
included. The data folder contains ticker reference lists.

## Reproducibility status

These notebooks document the original research workflow.
Running them requires API access, external datasets, and
updates to the original file paths. The price-mapping
preparation step is not included in this version.

Model development uses stratified random train, validation,
and test splits; these are not chronological holdout splits.