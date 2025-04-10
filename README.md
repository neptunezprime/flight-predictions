# FLIGHT PREDICTION.
# Predicting Fare of Airlines Tickets using Machine Learning

![image](https://github.com/user-attachments/assets/46842c45-3a19-4d0b-8f3a-6eb20e41b0ed)


Disclaimer⚠️: All datasets, info and reports in this repository do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual. All info are dummy and designed to demonstrate my advanced predictive ML modeling capabilities.

 # INTRODUCTION
  Flying into the Future with Machine Learning 

In an era where air travel has become the backbone of global connectivity, the volatility of airline ticket pricing remains a perplexing challenge for both travelers and industry analysts. From last-minute price surges to promotional deals, airfare pricing is influenced by a complex web of factors, ranging from booking time and travel season to airline competition and even fuel costs.
This project takes off at the intersection of aviation and artificial intelligence. By harnessing the power of machine learning, I attempt to demystify airfare pricing and develop a model that can accurately predict flight fares based on real-world variables. With the help of historical flight data and modern prediction algorithms, I not only forecast prices but also explore the patterns and insights hidden within airline fare structures.

Through feature engineering, exploratory data analysis, and model tuning, this project showcases how data science can be a powerful co-pilot, helping both travelers make informed decisions and airlines optimize pricing strategies.

![image](https://github.com/user-attachments/assets/965f2a64-59e1-4b90-a341-45ff2b739d14)

# PROBLEM STATEMENT:
. Airline ticket prices are unpredictable and vary based on multiple factors.

. Travelers face difficulty identifying the best time and fare to book flights.

The project aimed to:

. Analyze flight data with features like airline, route, stops, duration, and timings.

. Build a machine learning model to predict flight ticket prices accurately.

. Provide insights into key factors influencing fare variations.


# AIM:
* build a predictive model for airline ticket prices using machine learning.

* To identify key features that influence airfare fluctuations.

* To provide insights that benefit both travelers and airline pricing strategies.

# METHODOLOGY:
**Data Collection:**
Used a dataset containing flight details such as airline, source, destination, total stops, duration, and date-related fields.

**Data Preprocessing:**

* Handled missing values.

* Converted date, time, and duration features into numerical formats.

* Extracted and created new features (e.g., journey day, month, departure/arrival hour).

* Applied label encoding and one-hot encoding for categorical variables.

**Exploratory Data Analysis (EDA):**

* Visualized relationships between features and ticket prices.

* Identified key influencing factors such as total stops, airline, and travel duration.

**Feature Engineering:**

* Extracted meaningful insights from datetime columns.

* Standardized and normalized certain numerical features to improve model performance.

**Model Building:**

Implemented various regression models, including:

* Linear Regression

* Decision Tree Regressor

* Random Forest Regressor

**Model Evaluation:**

Compared models using metrics like:

* R² score

* Mean Absolute Error (MAE)

* Mean Squared Error (MSE)

* Selected the best-performing model for final predictions.

**Prediction:**

Used the trained model to predict ticket prices on unseen data.

# LIBRARIES:
**Data Manipulation and Analysis**
**Pandas:** Used for data cleaning, manipulation, and exploration, including handling missing values and creating data frames.
**NumPy:** Provides support for numerical operations, such as array manipulations and mathematical computations.

**Data Visualization**
**Matplotlib:** A plotting library for creating static, interactive, and animated visualizations (e.g., histograms, scatter plots).
**Seaborn**: Built on Matplotlib, it simplifies the creation of aesthetically pleasing and informative statistical graphics (e.g., heatmaps, boxplots).

**Machine Learning**
**Scikit-Learn:** The primary library for machine learning tasks such as model training, evaluation, hyperparameter tuning, and preprocessing (e.g., scaling, encoding).

**Environment and Workflow**
**Jupyter Notebook:** An interactive development environment for running and documenting Python code in a notebook format.
**Anaconda:** A distribution that simplifies Python package management and deployment, including pre-installed libraries for data science.
