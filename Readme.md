# SpaceX Falcon 9 First Stage Landing Prediction

This repository contains a complete data science and machine learning project to predict whether the Falcon 9 first stage will land successfully. The goal is to help estimate potential cost savings from reusable rockets and provide insights into launch success factors.

## 🚀 Project Overview

SpaceX's Falcon 9 rockets are partially reusable, which drastically reduces the cost of space launches. Predicting whether the first stage will successfully land allows competitors and collaborators to make informed financial and logistical decisions. This project includes data collection, cleaning, exploratory data analysis, visualization, and building machine learning models for prediction.


## 💻 Tech Stack & Libraries

**Python Version:** 3.8+

**Key Libraries:**

* `pandas`: For data manipulation and analysis
* `numpy`: For numerical operations
* `scikit-learn`: For machine learning model building (Logistic Regression, SVM, Decision Tree, KNN)
* `matplotlib`, `seaborn`: For data visualization and EDA
* `plotly`, `dash`: For interactive dashboards
* `folium`: For interactive maps
* `flask`: For serving models via API (if needed)
* `pickle`: For saving and loading trained models

**Tools:**

* **Jupyter Notebook:** Data exploration, preprocessing, model training
* **VS Code / PyCharm:** Application development
* **Git & GitHub:** Version control and collaboration

## 🤖 Machine Learning Models

**Algorithms Implemented:**

* `Logistic Regression`: For baseline classification performance
* `Support Vector Machine (SVM)`: To separate classes with different kernels (linear, rbf, sigmoid, poly)
* `Decision Tree Classifier`: For interpretable tree-based classification with hyperparameter tuning
* `K-Nearest Neighbors (KNN)`: For instance-based classification using distance metrics

**Techniques Used:**

* Hyperparameter tuning with `GridSearchCV` (10-fold cross-validation)
* Feature scaling using `StandardScaler`
* Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix
* Model comparison to select the best-performing classifier

## 📊 Dash Dashboard Features

* Pie chart showing launch success counts for all sites and specific sites
* Scatter plot visualizing Payload vs. Launch Outcome, colored by Booster Version
* Range slider for dynamic filtering of payload mass
* Interactive dropdown for selecting specific launch sites

## 🗺️ Folium Map Features

* Markers for launch sites and their proximity to coastlines, railways, and highways
* Color-coded markers showing launch outcomes
* Distance calculations displayed interactively

## 📈 Project Results

* The **Decision Tree Classifier** achieved the highest accuracy of **90%**.
* The best model confusion matrix showed:

  * True Positives (Landed): 12
  * True Negatives (Did Not Land): 4
  * False Negatives: 0
  * False Positives: 2
* Dashboards and maps provide interactive exploration of SpaceX data.

## 📝 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/spacex-landing-prediction.git
   cd spacex-landing-prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebooks to explore data and train models:

   ```bash
   jupyter notebook
   ```
4. Launch the Dash dashboard:

   ```bash
   python app/app.py
   ```
5. Open the dashboard in your browser at `http://127.0.0.1:8050`

## 📄 License

This project is for educational purposes as part of the IBM Data Science Capstone Course.

## 🙌 Acknowledgements

* IBM Skills Network & Coursera Capstone Project
* SpaceX API & Wikipedia for open data
* Community contributors on GitHub
