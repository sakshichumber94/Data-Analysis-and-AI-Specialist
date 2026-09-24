## AI Capstone Project – Auto Insurance Claim Severity Prediction

# Auto Insurance Claim Severity Prediction

## About the Project

This is my AI Capstone Project. The goal is to predict how much an auto insurance claim will cost.

When a person has a car accident, they file a claim with their insurance company. Some claims cost very little. Others cost a lot. This cost is called **claim severity**.

This project uses past claim data to train a machine learning model. The model learns patterns from old claims and predicts the cost of new ones.

## Why It Matters

If an insurance company can predict claim cost early, it can:

- Set aside the right amount of money for each claim
- Send expensive claims to experienced staff faster
- Process small claims quickly
- Spot claims that look unusual

## Problem Type

This is a **supervised learning – regression** problem. The model predicts a number (the claim amount), not a category.

## Project Steps

1. **Data exploration** – Understand the data, check for missing values, and look at the claim amounts.
2. **Data cleaning** – Fix or remove bad data.
3. **Feature engineering** – Turn text columns into numbers the model can use.
4. **Model training** – Start with a simple model, then try stronger ones.
5. **Evaluation** – Measure how close the predictions are to the real costs.

## Tools Used

- Python
- pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn
- Jupyter Notebook

## Evaluation Metric

**MAE (Mean Absolute Error)** – the average difference between the predicted cost and the real cost. Lower is better.

## Status

🚧 In progress
