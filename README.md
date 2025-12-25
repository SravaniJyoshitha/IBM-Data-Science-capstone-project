# IBM-Data-Science-capstone-project
🚀 SpaceX Falcon 9 Launch Success Prediction

📌 Project Overview

SpaceX significantly reduces the cost of space missions by reusing the Falcon 9 first stage. The success of a Falcon 9 landing directly impacts launch cost and mission planning.

This project aims to predict whether the Falcon 9 first stage will successfully land using historical launch data and machine learning techniques.

🎯 Objectives

Collect SpaceX launch data using APIs and web scraping

Perform exploratory data analysis (EDA) and visualization

Build machine learning models to predict launch success

Identify key factors influencing Falcon 9 landing outcomes

📊 Dataset

Source:

SpaceX REST API

Web scraping from Wikipedia

Target Variable: Class

1 → Successful Landing

0 → Failed Landing

Key Features

Launch site

Orbit type

Payload mass

Booster version

Number of previous launches

🛠️ Technologies Used

Programming Language: Python

Libraries & Tools:

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Folium (interactive maps)

BeautifulSoup (web scraping)

SQL (data querying)

🔍 Project Workflow

Data Collection

Extracted launch data using SpaceX API

Scraped launch tables from Wikipedia

Data Wrangling

Cleaned missing and inconsistent values

Converted categorical variables

Exploratory Data Analysis (EDA)

Visualized payload mass vs launch success

Analyzed success rates by orbit and launch site

Interactive geospatial analysis using Folium

Feature Engineering

Feature scaling

Model Building

Logistic Regression

Support Vector Machine (SVM)

Decision Tree

K-Nearest Neighbors (KNN)

Model Evaluation

Accuracy score

Confusion matrix

Model comparison

📈 Results & Insights

Launch success is strongly influenced by payload mass and orbit type

Certain launch sites have higher success rates

Decision Tree Model achieved better performance than baseline models with accuracy of 87%
