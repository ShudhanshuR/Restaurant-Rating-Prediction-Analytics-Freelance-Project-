# Restaurant-Rating-Prediction-Analytics (Freelance-Project)
_____________________________________________________________
# Project Overview
- This project was developed as a part of a Freelance Data Science engagement with Cognifyz Technologies. The objective was to perform deep-dive analytics and build a predictive model for restaurant ratings using a real-world dataset (Zomato Case Study).

# Business Problem Statement
_________________________________
- In the highly competitive food-tech industry, customer ratings are the ultimate metric for success. For this project, I was tasked to:

- Analyze the drivers of success: Identify which features (Cost, Cuisine, Services) most significantly impact a restaurant's aggregate rating.

- Predictive Modeling: Build a machine learning regression model to accurately forecast the rating of any restaurant based on its operational profile.

# Real-World Data Pipeline & Extraction
____________________________________________
- A key highlight of this project is the data handling process:

- Database Extraction: Unlike static Kaggle projects, the data for this analysis was integrated and extracted from a structured database environment.

- Data Integrity: Performed rigorous data cleaning, handled missing values (especially in Cuisines), and treated outliers in the 'Average Cost for Two' to ensure model reliability.
  
## Key Business Insights
____________________________
- Engagement vs. Rating: A strong positive correlation was found between the number of Votes and the Aggregate Rating, suggesting that customer engagement is a primary driver of visibility.

- Service Impact: Restaurants offering both Online Delivery and Table Booking showed significantly higher average ratings compared to those without these services.

- Price Positioning: Most restaurants fall into 'Price Range 2', but the highest-rated ones are often strategically priced in 'Price Range 3 & 4'.

## Technical StackLanguage:
_______________________________
- PythonData Extraction & Cleaning: SQL, Pandas, NumPyVisualization: Matplotlib, SeabornMachine Learning: Scikit-Learn (Linear Regression, Decision Tree, Random Forest)Evaluation: RMSE, R-Squared ($R^2$)

##  Model Implementation
___________________________
- Preprocessing: Applied Label Encoding for categorical variables like City and Locality.

- Feature Selection: Focused on features like Price Range, Votes, and Service availability.

- Model Optimization: Trained multiple regressors. The Random Forest Regressor delivered the best performance with high precision in predicting ratings.

## Strategic Recommendations for Stakeholders
________________________________________________
- Boost Voter Participation: Encourage restaurants to actively seek feedback to increase their 'Votes' count, which directly correlates with higher ratings.

- Digital Transformation: For low-rated restaurants, enabling 'Online Delivery' is the fastest way to improve customer reach and rating potential.

Developed as a Freelance Project for Cognifyz Technologies.
- Developed by Shudhanshu Ranjan
