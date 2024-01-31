# Mall Customer Clustering

## Description

This project utilizes a dataset containing information on individuals' salary and spending score to perform k-means clustering. The goal is to identify distinct customer segments for targeted marketing strategies. In particular, we aim to recommend products to people with high income and low spending while avoiding recommendations for individuals with low income and high spending.

## Features

- **Clustering Features from dataset:** Salary, Spending Score
- **Algorithm:** K-means clustering

## Clustering Algorithm

We chose the k-means clustering algorithm due to its simplicity and efficiency in partitioning data into distinct clusters based on similarity.

## Dataset

The dataset used in this project contains information on individuals' salary and spending score. It was obtained from [www.kaggle.com] and preprocessed to handle any missing values or outliers.

## Results

The k-means clustering algorithm grouped individuals into five clusters:

1. **High Income, Low Spending:** Individuals with high income and low spending.
2. **High  Income, High Spending:** Individuals with high income and high spending.
3. **Low  Income, Low Spending:** Individuals with low income and low spending.
4. **Low Income, High Spending:** Individuals with low income and high spending.
5. **Normal:** Individuals with moderate income and spending behavior.
