🚀 Falcon 9 First Stage Landing Prediction - IBM Data Science Capstone Project
This project is part of the IBM Data Science Capstone. The goal is to predict the landing success of the SpaceX Falcon 9 rocket’s first stage using machine learning techniques. Falcon 9’s reusability is a key factor in reducing space launch costs, and this project explores the relationship between payloads, launch sites, and other variables with the success rate of landings.

📖 Project Overview
SpaceX Falcon 9 rocket launches cost significantly less than competitors due to its ability to reuse the first stage booster. Predicting whether a Falcon 9 launch will result in a successful booster landing is critical for estimating costs and evaluating reusability performance.

This project includes:

Data collection from SpaceX API and Wikipedia

Data wrangling and preprocessing

Exploratory data analysis (EDA)

Interactive analytics with Folium and Dash

Machine learning model development and evaluation

🛠️ Technologies Used
Python 3.x

Pandas, NumPy for data manipulation

Matplotlib, Seaborn, Plotly for visualization

Folium for interactive maps

Dash for building interactive dashboards

Scikit-Learn for machine learning models

SQLite for SQL queries

🧪 Machine Learning Models
We built and compared several classification models to predict the landing success:

Model	Accuracy (%)
Logistic Regression	85%
Support Vector Machine	88%
Decision Tree	90%
K-Nearest Neighbors	87%

✅ Best Model: Decision Tree Classifier with 90% accuracy.

📊 Interactive Dashboard
An interactive dashboard was built using Dash:

Visualizes launch success rates across sites.

Allows payload range selection and site filtering.

Shows correlations between payload and success outcomes.

🌎 Visual Analytics
Created interactive maps using Folium:

Displayed launch sites and outcomes.

Calculated proximity to nearby infrastructure (railways, highways, coastlines).
📈 Project Results
The Decision Tree model achieved the highest classification accuracy (90%).

Payloads in the 2000–6000kg range showed higher landing success rates.

Interactive visualizations revealed key correlations between launch parameters and outcomes.

👨‍💻 Author
Ayush Nagras

IBM Data Science Capstone Project
