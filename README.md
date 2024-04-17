# Customer Churn ML Model with Predictive Analytics

This project aims to develop a machine learning model to predict customer churn for ExtraaLearn, an EdTech startup. Utilizing predictive analytics, this model helps identify leads most likely to convert into paying customers, enabling the company to optimize resource allocation and enhance targeting strategies.

## Technologies

The project leverages python 3.7 with the following packages:

* [Python 3.7.13](https://www.python.org/downloads/release/python-385/) - The programming language used in the project.
* [Pandas](https://pandas.pydata.org/) - A Python library used for efficient data manipulation.
* [Jupyter Lab](https://jupyter.org/) - An interactive development environment used to create and share documents containing live code, equations, visualizations, and narrative text.
* [Numpy](https://numpy.org/) - A library for the Python programming language, adding support for large, multi-dimensional arrays and matrices.
* [Scikit-learn](https://scikit-learn.org/stable/index.html) - A Python library containing efficient tools for machine learning and statistical modeling, including classification, regression, clustering, and dimensionality reduction.
* [Seaborn](https://seaborn.pydata.org/) - For high-level interface for drawing attractive and informative statistical graphics.
* [Imbalanced-learn](https://imbalanced-learn.org/stable/) For dealing with the imbalanced dataset with the application of SMOTE.

## Installation

* Install Python 3.7 (if not installed already)
* Download and install the Anaconda Python distribution, which includes Python, the Jupyter Notebook App, and other commonly used packages for scientific computing and data science.
* Before running the project, ensure you have Python 3.7 installed. Use the following commands to install the required libraries:
```
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```
* Open the project **customer_churn.ipynb** bJupyter Notebook file in the browser to explore the dataset, run the models, and view the results.

## Project Breakdown

#### Data Exploration and Preprocessing
The project begins with an exploratory data analysis (EDA) to understand the dynamics within the data, focusing on patterns that could influence the model's predictions. The preprocessing phase includes:

* **Data Cleaning:** Handling missing values and erroneous data entries.
* **Feature Engineering:** Creating new features that can improve model predictions.
* **Data Transformation:** Encoding categorical variables and normalizing data to prepare for machine learning.

#### Model Development and Evaluation
Several machine learning models are tested, including Logistic Regression, Decision Trees, and Random Forests. The models are evaluated based on accuracy, precision, recall, F1-score, and AUC-ROC to determine the best performer.

#### Model Optimization
The project utilizes techniques such as SMOTE for handling class imbalance and GridSearchCV for hyperparameter tuning to enhance model performance.

#### Reporting
The final phase involves generating comprehensive reports that detail the model's performance, including key metrics and feature importances, to provide insights into which variables most significantly impact customer churn.

### Contributors

Alexander Likhachev

### License
MIT
