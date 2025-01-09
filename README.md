# carquest

# Project Overview:
This program is a Car Recommender System designed to help users find vehicles tailored to their specific preferences, such as brand, price range, and location. By processing user inputs, it queries a database to provide personalized car recommendations and answers questions like identifying the most fuel-efficient car. The program combines machine learning and database management to offer insightful and actionable suggestions, with room for enhancing the user interface for a seamless experience.

# Technical Overview:

Features:
Dynamic Car Recommendations: 
- Allows users to search for cars by brand, price range, and city.
- Retrieves matching vehicles from an SQLite database and presents them in a user-friendly format.

Data Insights: 
- Identifies the most fuel-efficient car in the dataset and provides related details.

Model Integration:
- Trains a Random Forest Regressor to predict car prices based on attributes like brand, mileage, fuel type, and transmission.
- Evaluates model performance using Mean Squared Error (MSE) and R-squared metrics to ensure reliability.

Interactive Features
- Collects user input for queries and dynamically adjusts recommendations based on preferences.
- Handles invalid user inputs with error prompts and clear instructions.

Database Management
- Converts preprocessed data into an SQLite database for efficient querying and storage.
- Utilizes SQL queries to filter cars based on user criteria.

Programming Insights:
- Coded in Python
- Pandas: For data cleaning, preprocessing, and feature engineering.
- Scikit-Learn: To build and evaluate the Random Forest regression model.
- SQLite3: Manages a relational database for storing and querying car data.
- LabelEncoder: Encodes categorical variables like brand and city for seamless model training and database interaction.

Database Querying
- Encodes user inputs into compatible formats for efficient SQL queries.
- Dynamically filters cars based on user preferences, such as brand, price range, and city.

Machine Learning Pipeline
- Splits the data into training and testing sets for validation.
- Predicts car prices based on features, offering insights into market trends.

# Interactive Elements
- Engages users through dynamic input queries for personalized recommendations.
- Answers specific queries, such as identifying the most fuel-efficient car in the dataset.

# Key Applications:
- Personalized Car Recommendations: Helps users find cars that match their budget and preferences.
- Market Insights: Provides actionable insights, such as identifying fuel-efficient cars or price predictions.
- Enhanced Decision-Making: Supports buyers and sellers with data-driven recommendations and analysis.

This project exemplifies the integration of machine learning, database management, and interactive features, showcasing a robust solution for personalized car recommendations and market insights.
