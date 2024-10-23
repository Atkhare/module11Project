# module11Project
This is a Machine learning project for module 11. 
The link to model code is -(https://github.com/Atkhare/module11Project/blob/main/module11Project.ipynb)

#### Business Understanding
From a business perspective, we are tasked with identifying key drivers for used car prices. In the CRISP-DM overview, we are asked to convert this business framing to a data problem definition. Using a few sentences, reframe the task as a data task with the appropriate technical vocabulary.

The business objective is to identify the critical attributes from Vehicle datasets and generate a model that can predict the price when key attributes are passed to the model. The important car features will help the salesperson sell used cars to buyers. To achieve the results the vehicle dataset is downloaded from the Kaggle machine learning website which gives insight into used car attributes.

The success criteria of this project are to identify the key features and create a functional model that can be used by Car dealers to drive the sales of used Cars.

This project will utilize multiple Python packages & APIs and resources from open-source content to develop a model.

#### Data Understanding
This step is to get familiar with Data and identify any quality issues in the dataset. The focus will be on:

1. Upload the vehicle dataset for analysis and model generation.
2. Data analysis of numerical & categorical features and performing the quality check on attributes.
3. Identify data incompleteness and attributes which is irrelevant due to missing data and can be dropped.

#### Data Preparation

The following data cleanup exercise is done as per the previous data analysis & to prepare the data for Modelling:

1. Drop the Identified columns due to the high percent of missing data or
2. Drop the rows having more than 5 NAN columns
3. Remove Junk characters from the datasets
4. Use Data impute techniques to fill in missing data for both numeric & categorical fields
5. Encode the data so that it can be executed in various models
6. Scale the dataset and split the Test and Train datasets
7. Analyze the dataset correlation between feature
8. And run PCA against to analyze the dataset dimensionality

#### Modeling

After the data preparation, generate models to evaluate the price of used cars and compare the models.  

1. Linear Regression with polynomial features and sequential feature selection
2. Ride Regression Model with Lasso feature selector
3. Linear regression Model with polynomial features and Lasso feature selection
4. Lasso Regression Model with polynomial features
5. Calculated the MSE on Test and Training datasets for comparison

#### Conclusion
Evaluating the MSE based on Training & Test scaled data, the model Linear Regression with Lasso selector and polynomial features is giving better results compared to other Models. Therefore selecting this model for the final Car price evaluation and presenting it to Car dealers.

#### Deployment
The key features to focus on by dealers which can give better prices on the car are :

1. Car Manufacturer
2. Region
3. State
4. Year of manufacture
5. Low Odometer reading

Other attributes to consider are:

1. Fuel Efficiency
2. Condition of Car

There is a direct dependency on Car price related to the manufacturer and state car is sold. The inventory of used cars can be arranged based on such car manufacturers.

Also, the low odometer reading and year of manufacture are related and attributed to the high price of the car.
