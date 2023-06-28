# Robust yield prediction of various farm processing units
## Problem Description:
A new fast food chain is seeing rapid expansion over the past couple of years. They 
are now trying to optimize their supply chain to ensure that there are no shortages of 
ingredients. For this, they’ve tasked their data science team to come up with a model that could predict the output of each food processing farm over the next few years. 
These predictions could further increase the efficiency of their current supply chain 
management systems. 
In this competition we are expected to build a machine learning model(s) that could predict the output of the food processing farms for the next year.

### About Data:
There are 5 datasets along with a sample submission file provided to you in this 
competition. The datasets are named as follows:
#### ‘train_data.csv’:
1. date: The timestamp at which the yield of the food processing farm was measured
2. farm_id: The farm identifier that recognizes the farm food processing plant
3. ingredient_type: The type of ingredient being produced
4. yield: The yield of the plant in tonnes
#### ‘farm_data.csv’:
1. farm_id: The farm identifier that recognizes the farm food processing plant
2. founding_year: They year when the operations commenced on the farm and food processing plant. 
3. num_processing_plants: The number of processing plants present on the farm
4. farm_area: The area of the farm in square meters
5. farming_company: The company that owns the farms
6. deidentified_location: The location at which the farm is present
#### ‘train_weather.csv’:
1. For each location where the farms are present, the weather data is also provided by timestamp
● ‘test_data.csv’ and ‘test_weather.csv’ are also provided to you

#### Objectives:
In this hackathon, you are expected to: 
1. Explore the data and engineer new features
2. Predict the yield for each farm during the given timestamps
3. Given the forecasted demand for the next few months for a particular ingredient, device a strategy to source it
Creating a strategy to source ‘ing_w’ ingredient type
