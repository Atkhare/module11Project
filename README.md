# module11Project
This is a Machine learning project for module 11. 

#### Business Understanding
From a business perspective, we are tasked with identifying key drivers for used car prices. In the CRISP-DM overview, we are asked to convert this business framing to a data problem definition. Using a few sentences, reframe the task as a data task with the appropriate technical vocabulary.

The business objective is to identify the critical attributes from Vehicle datasets and generate a model that can predict the price when key attributes are passed to the model. The important car features will help the salesperson sell used cars to buyers. To achieve the results the vehicle dataset is downloaded from the Kaggle machine learning website which gives insight into used car attributes.

The success criteria of this project are to identify the key features and create a functional model that can be used by Car dealers to drive the sales of used Cars.

This project will utilize multiple Python packages & APIs and resources from open-source content to develop a model.

#### Data Understanding
After considering the business understanding, we want to get familiar with our data. Write down some steps that you would take to get to know the dataset and identify any quality issues within. Take time to get to know the dataset and explore what information it contains and how this could be used to inform your business understanding.

In this section, the focus will be on

Upload the vehicle dataset for analysis and model generation.
Data analysis of numerical & categorical features and performing the quality check on attributes.
Identify data incompleteness and attributes which is irrelevant due to missing data and can be dropped.

#### Data Preparation
After our initial exploration and fine-tuning of the business understanding, it is time to construct our final dataset before modeling. Here, we want to make sure to handle any integrity issues and cleaning, the engineering of new features, any transformations that we believe should happen (scaling, logarithms, normalization, etc.), and general preparation for modeling with sklearn.

The following data cleanup exercise is done as per the previous data analysis & to prepare the data for Modelling:

Drop the Identified columns due to the high percent of missing data or
Drop the rows having more than 5 NAN columns
Remove Junk characters from the datasets
Use Data impute techniques to fill in missing data for both numeric & categorical fields
Encode the data so that it can be executed in various models
Scale the dataset and split the Test and Train datasets
Analyze the dataset correlation between feature
And run PCA against to analyze the dataset dimensionality

#### Modeling
With your (almost?) final dataset in hand, it is now time to build some models. Here, you should build a number of different regression models with the price as the target. In building your models, you should explore different parameters and be sure to cross-validate your findings.

Generated the following models to evaluate the Vehicle data frame

Linear Regression with polynomial features and sequential feature selection
Ride Regression Model with Lasso feature selector
Linear regression Model with polynomial features and Lasso feature selection
Lasso Regression Model with polynomial features
Calculated the MSE on Test and Training datasets for comparison
Final dataset for Modelling

#### Conclusion
Evaluating the MSE based on Training & Test scaled data, the model Linear Regression with Lasso selector and polynomial features is giving better results compared to other Models. Therefore selecting this model for the final Car price evaluation and presenting it to Car dealers.

#### Deployment
Now that we've settled on our models and findings, it is time to deliver the information to the client. You should organize your work as a basic report that details your primary findings. Keep in mind that your audience is a group of used car dealers interested in fine-tuning their inventory.

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
