# PureWaterInsight

# Overview
PureWaterInsight is a machine learning project aimed at predicting the potability of water. Using the water_potability.csv dataset, which includes various water quality metrics for 3276 water bodies, this project determines whether water is safe for human consumption.

# Dataset

The dataset includes the following water quality metrics:

pH value: Indicator of the acidic or alkaline condition.
Hardness: Measures the concentration of calcium and magnesium salts.
Solids (TDS): Total dissolved solids, indicating mineralization level.
Chloramines: Disinfectants used in public water systems.
Sulfate: Naturally occurring substances found in minerals and soil.
Conductivity: Electrical conductivity based on ion concentration.
Organic Carbon: Total amount of carbon in organic compounds.
Trihalomethanes: Chemicals found in chlorinated water.
Turbidity: Measure of solid matter in suspended state.
Potability: Indicates if water is safe for consumption (1 = Potable, 0 = Not potable).
Goals
Develop a machine learning model to predict water potability.
Provide insights into water quality metrics affecting safety

the Dataset could be found here: https://www.kaggle.com/datasets/adityakadiwal/water-potability

# Model Performance
After training the model using a Random Forest classifier and tuning its hyperparameters, the following results were obtained:

Hyperparameter Tuning
The Random Forest model was tuned using the following parameter grid:

Number of Estimators: 50, 100, 200
Maximum Depth: None, 10, 20, 30
Minimum Samples Split: 2, 5, 10
Minimum Samples Leaf: 1, 2, 4
Bootstrap: True, False
The best parameters found through GridSearchCV were:

Bootstrap: True
Max Depth: None
Min Samples Leaf: 1
Min Samples Split: 2
Number of Estimators: 200
Test Data Accuracy
The accuracy of the model on the test data was 0.745.
