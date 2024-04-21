# Introduction of Project
Flight Fare prediction using machine learning. In this project, we will be analyzing the flight fare dataset using essential exploratory data analysis techniques then will draw some predictions about the price of the flight based on some features such as what type of airline it is, what is the arrival time, what is the departure time, what is the duration of the flight, source, destination and more.

- EDA: Learn the complete process of EDA

- Data analysis: Learn to withdraw some insights from the dataset both mathematically and visualize it.

- Machine learning model: Learn to make a Machine learning model after the data preprocessing steps.

- Comparing the models: We will be working on multiple models so that we could choose the best one for that we need to know the techniques of how to compare our model to choose the best one so we will be covering that also.

# Abstract:
Passengers are attempting to grasp how these airline businesses make judgments regarding flight ticket costs over time, since demand for air travel in India is growing more popular with multiple flight tickets purchasing on the internet. There are a variety of strategies that allow you to perform things at the right moment. Customers want the cheapest ticket possible, but airlines want to maximize their profit by keeping their entire income as high as feasible. To increase revenue, airlines use a number of computational tactics, including as demand forecasting and pricing discrimination. This is for the consumer who buys a flight ticket by estimating the amount of the flight fare. The major difficulty from the customer’s perspective, finding the perfect value or the ideal time to purchase tickets is the most difficult component. The bulk of the techniques rely on advanced computational intelligence, prediction models, and a branch of science called Machine Learning (ML). This research emphasizes the factors and provides instructions for developing a machine learning-based aircraft fare prediction model.

## Evaluate dataset into multiple steps:
1. Data Collection
2. Loading data
3. Domain Analysis
4. Basic Checks of data
5. EDA (Univariate Data Analysis)
6. Data Pre-processing
7. Feature Selection
8. Building ML Model
9. Hyperparameter Tuning
10. Training & Model Evaluation

## Loading Dataset:
load data in python using panda’s library

## Attribute Information :
1. Airline: So this column will have all the types of airlines like Indigo, Jet Airways,
Air India, and many more.
2. Date_of_Journey: This column will let us know about the date on which the
passenger’s journey will start.
3. Source: This column holds the name of the place from where the passenger’s
journey will start.
4. Destination: This column holds the name of the place to where passengers
wanted to travel.
5. Route: Here we can know about what the route is through which passengers
have opted to travel from his/her source to their destination.
6. Arrival_Time: Arrival time is when the passenger will reach his/her destination.

7. Duration: Duration is the whole period that a flight will take to complete its
journey from source to destination.
8. Total_Stops: This will let us know in how many places flights will stop there for
the flight in the whole journey.
9. Additional_Info: In this column, we will get information about food, kind of food,
and other amenities.
10. Price: Price of the flight for a complete journey including all the expenses
before onboarding.

## Model Creation & Evaluation
- Define Independent and dependant variable and split the data into training and testing.
-  For Training 80% & Testing 20% data
- Check data is balanced or not after check the data has imbalanced so I utilized the SMOTE technique to balance the data.
- Use regression algorithms including Linear Regression, Random Forest,XGBoost and Hyperparameter Tuning. 
-  Afterward, evaluate the models using accuracy and regression metrics.

## Best Model
- Our best performed model with accuracy (0.84) metric is XG Boost. This regression could achieve accuracy rate 0.84 that is average accuracy.

# Conclusion
- In a project focused on improving sales by identifying high-quality leads, various machine learning models were tested using a dataset. The goal was to find the most effective model based on different performance measures like Accuracy, MSE, MAE, RMSE, R2 Score. • After evaluating these models, it was determined that the XG Boosting outperformed the others by achieving the highest accuracy score. This suggests that, compared to the other models tested, XG Boosting was most successful in accurately predicting lead quality, making it the top performer for this particular task.
