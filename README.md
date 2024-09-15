# Big-Mart-Sales-Prediction
This project involves predicting the sales of various items sold by supermarkets using machine learning techniques. The dataset includes multiple features related to the items and outlets, such as:

Item Features: Item Weight, Item Identifier, Item Fat Content, Item Visibility, Item Type, Item MRP.
Outlet Features: Outlet Identifier, Outlet Size, Outlet Establishment Year, Outlet Location Type, Outlet Type.
Workflow:
Data Preprocessing:

Handled missing values in the dataset.
Plotted graphs to visualize the distribution of various features and identify any irregularities.
Addressed inconsistencies in categorical features (e.g., similar labels).
Feature Engineering:

Used label encoding to transform categorical features into numerical format, preparing the dataset for machine learning.
Model Training:

Applied the XGBoost Regressor algorithm to train the model on the processed dataset.
Model Evaluation:

Evaluated model performance using the R-squared score, which measures how well the model fits the data.
