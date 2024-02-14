## Project Overview
This repository hosts a machine learning project aimed at predicting and visualizing deviations in Instrument Landing System (ILS) ground check data relative to standard flight check references. By analyzing the Difference in Depth of Modulation (DDM), Sensitivity in Depth of Modulation (SDM), and angle measurements from both flight and ground checks, I develop a model that not only predicts these deviations but also plots the predicted DDM and SDM values against the flight check standards. This dual approach of prediction and visualization facilitates a comprehensive understanding of the ILS's operational integrity and aids in the proactive maintenance of its components.

## Background
The accuracy and reliability of ILS are critical for aircraft landings in low-visibility conditions. Regular maintenance, verified through flight and ground checks, ensures the system's performance. This project introduces an innovative method to streamline the analysis of ILS maintenance checks, leveraging predictive modeling and data visualization to enhance system reliability and safety.

## Methodology
- **Data Preparation**: Preparing and structuring flight and ground check data for comprehensive analysis.
- **Deviation Analysis and Prediction**: Calculating deviations and using the CatBoost algorithm (will explore other algorithms as well) to predict their magnitudes.
- **Visualization**: Plotting predicted deviations in DDM and SDM values against standard flight check values to assess model accuracy and system alignment.
- **Feature Engineering**: Identifying and integrating additional features to improve predictive accuracy.

## Technologies Used
- JupyterHub for the entire project work.
- Python for data processing, modeling, and visualization.
- CatBoost for robust predictive modeling.
- Matplotlib/Seaborn for generating insightful visualizations.
