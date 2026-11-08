Netflix Data Science Project

Project Overview

This project focuses on analysing Netflix content using Python and Data Science techniques. It explores the Netflix dataset to understand content distribution, identify trends, build a recommendation system, and predict content release patterns.

The project was completed as part of the Auspify Technologies Data Science Internship.

Project Objectives

The main objectives of this project are to:

Clean and preprocess the Netflix dataset.

Perform Exploratory Data Analysis (EDA).

Identify patterns in Netflix movies and TV shows.

Develop a content-based recommendation system.

Analyse historical release trends and predict future trends.

Dataset Description

The project uses a Netflix dataset named Dataset.csv.

The dataset contains information about Netflix movies and TV shows, including:

Show ID

Type

Title

Director

Cast

Country

Date Added

Release Year

Rating

Duration

Listed In (Genres)

Description

Technologies and Libraries Used

The following tools and Python libraries were used:

Python

Pandas – Data manipulation and cleaning.

NumPy – Numerical operations.

Matplotlib – Data visualization.

Seaborn – Statistical visualization.

Scikit-learn – Machine learning and recommendation system development.

Project Tasks

Task 1: Data Cleaning and Preprocessing

The dataset was inspected and prepared for analysis.

Activities included:

Loading the dataset.

Checking dataset structure and information.

Identifying missing values.

Checking and removing duplicate records.

Cleaning text columns.

Converting date columns into the appropriate date format.

Saving the cleaned dataset.

Task 2: Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the Netflix dataset.

Activities included:

Comparing the number of movies and TV shows.

Analysing content distribution by country.

Identifying the most common genres.

Analysing content by release year.

Exploring the number of titles added to Netflix over time.

Creating charts and visualizations to communicate findings.

Task 3: Netflix Recommendation System

A content-based recommendation system was developed using TF-IDF and Cosine Similarity.

The system analyses information such as:

Content type.

Genre.

Director.

Country.

It uses these features to identify and recommend titles with similar characteristics.

Task 4: Trend Prediction Analysis

A Linear Regression model was developed to analyse Netflix content release trends.

The model used historical release-year information to predict the number of titles released.

Model Evaluation Results

Model

MAE

RMSE

Baseline Model

505.98

629.55

Linear Regression

475.14

603.20

The Linear Regression model performed better than the baseline model because it achieved lower MAE and RMSE values.

However, the prediction errors indicate that the model still has limitations.