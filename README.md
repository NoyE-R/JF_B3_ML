﻿# JF_B3_ML

# Presentation of the repository
- Three Machine Learning projects of the Jedha Bootcamp certification (Data Fullstack) including linear regression, classification and clustering analysis.
- Contact e-mail: [contact](noyer.estelle@gmail.com)

# Studied projects in this repository
- Walmart Sales: project aiming to describe the main features impacting the walmart store sales on a subsample of the complete dataset from Kaggle competition (link). -> Linear Regression
- Conversion Rate: project aiming to predicting the number of new subscriber to web site newsletter. -> Classification
- Uber PickUp: project aiming to identify the hot zones at Manhattan per day and hour of the day during September 2014. -> Clustering

# Folder organization
- Each folder are including working dataset files, script (Jupyter notebook) with EDA, tested models and graphics.
- Walmart_Sales:
    - EDA_ML_LinearRegression.ipynb: script with EDA and tested models
    - Walmart_Store_sales.csv: working dataset

- Conversion_Rate:
    - EDA_ML_Classification.ipynb: script with EDA and tested models
    - conversion_data_train.csv: dataset used to train models
    - conversion_data_test.csv: dataset used to test models (for a challenge)
    - conversion_data_test_predictions_voting.csv: predictions of conversion_data_test.csv using the best developed model
    - models folder: save of the tested models

- Uber_PickUp:
    - EDA_ML_Cluster.ipynb: script with EDA and tested models
    - uber-raw-data-sep14.csv: used dataset with data of september 2014
    - results folder: saved output from DBSCAN model
        - DBscan_coordcluster_DayHour.csv: average coordinates of hot zones detected by clustering (DBscan model) per day of the week and hour of the day
        - DBscab_nbcluster_DayHour.csv: number of detected cluster/hot zone by DBscan model per day of the week and hour of the day
        - DBscan_output_model.csv: cluster number attribution for each reported Uber pick-up

# Additional information
- Python version: 3.10.8
- Main used librairies: pandas, scikit-learn, plotly, numpy
