# 102316104_UCS654_Assignment6_Data-Generation-using-Modelling-and-Simulation-for-ML
# Data Generation using Modelling and Simulation for Machine Learning

## Overview

This project focuses on generating synthetic data using modelling and simulation, and then applying multiple Machine Learning models to identify the best performing one.

## Simulation Tool Used

I used **SimPy (Python library)** to simulate a queue system. The system models customer arrivals and service processes similar to a bank or hospital queue. The goal was to predict the **average waiting time** based on system parameters.

## Parameters and Bounds

The following parameters were randomly generated within defined ranges:

- Arrival Rate: 1 to 10  
- Service Rate: 1 to 8  
- Number of Servers: 1 to 5  

These parameters were passed into the simulator.

## Data Generation

A total of **1000 simulations** were generated. For each simulation, the average waiting time was recorded. This created a dataset of 1000 samples for ML training.

## ML Models Compared

The following models were evaluated:

- Linear Regression  
- Decision Tree  
- Random Forest  
- KNN  
- SVR  
- Gradient Boosting  
- MLP Regressor  

Evaluation metrics used: MAE, RMSE, and R² Score.

## Conclusion

After comparison, Random Forest performed best with highest R² and lowest error. This project demonstrates how simulation-based data can be effectively used for machine learning model selection.
