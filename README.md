# house_price_prediction
Project Overview

This project analyzes the Gurgaon real estate market using a dataset of 4,000+ property listings with 19 features. The goal was to understand what truly drives property prices, build reliable price prediction models, and create a simple recommendation system to help users find suitable apartments based on their preferences.

The project combines data exploration, feature selection, predictive modeling, and recommendation system design to simulate a real-world real estate analytics use case.

Dataset Description

Location: Gurgaon, India

Records: 4,000+ residential properties

Features: 19 attributes including location, size, number of bedrooms, amenities, property type, and pricing information

Target Variable: Property price

Data Preprocessing & Exploratory Data Analysis

Cleaned the dataset by handling missing values, duplicates, and inconsistent entries

Performed univariate EDA to understand price distributions, property sizes, and category-wise trends

Conducted multivariate EDA to analyze relationships between price and factors such as:

Location

Property size and layout

Amenities

Property category

Identified key patterns and trends influencing pricing across different property segments

Feature Selection & Interpretability

To improve model performance and interpretability:

Applied Correlation Analysis to remove redundant variables

Used Recursive Feature Elimination (RFE) to select the most impactful features

Leveraged Permutation Importance to validate feature contributions

Focused on keeping features that were both predictive and meaningful from a business perspective

Model Development & Evaluation

Multiple regression-based models were developed and compared:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Best model performance:

R² Score: 0.90

Mean Absolute Error (MAE): 0.25

The models demonstrated strong predictive capability, accurately estimating property prices while capturing non-linear relationships in the data.

Recommendation System

In addition to price prediction, a content-based recommendation system was designed:

Recommends apartments based on:

Budget range

Amenities

Property characteristics

Uses similarity between property features to suggest alternatives

Helps users discover properties aligned with their preferences without relying on user history

Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Key Takeaways

Gained hands-on experience with real estate market analysis

Learned how feature selection improves both performance and interpretability

Built end-to-end ML workflows from raw data to deployment-ready insights

Combined predictive modeling with recommendation systems for practical use cases
