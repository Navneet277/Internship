# Internship
Repository containing internship tasks
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Task 1:
  
  # Iris Classification Project:
--> This project is part of my internship work, aimed at building a machine learning model to classify iris species based on their features. The dataset used is the classic Iris Dataset, which contains sepal and petal measurements for three iris species: Iris-setosa, Iris-versicolor, and Iris-virginica.

  # Task Overview:
--> Build a logistic regression model to classify iris species.
    Perform data exploration and preprocessing.
    Evaluate the model's performance using metrics like accuracy, confusion matrix, and classification report.

  # Project Structure:
  Task1_Iris_Classification/
  
  ├── Visuals/
  
  │   └── ClassDistribution.png  
  
  │   └── ConfusionMatrix.png 
  
  │   └── Output_Model.png 
  
  │   └── Relationships_Pairplot.png
  
  ├── data/
 
  │   └── Iris.csv               # Dataset file
  
  ├── iris_classification.ipynb  # Jupyter Notebook for detailed workflow
  
  ├── iris_classification.py     # Python script for model training and evaluation
  
  ├── requirements.txt           # Required Python libraries
  
  ├── README.md                  # Project documentation

  # How to Run the Project:
  Prerequisites:  Python 3.7 or higher
  Required libraries (see requirements.txt)

  # Steps:
  Clone the Repository:
  git clone https://github.com/your-username/your-repo-name.git
  cd Task_1_Iris_Classification

  # Install Dependencies:
  pip install -r requirements.txt

  # Run the Code:
  To execute the Python script:
  
  python iris_classification.py
  
  Alternatively, open the Jupyter Notebook iris_classification.ipynb for a step-by-step walkthrough.

  # Dataset Description:
  The Iris Dataset contains 150 rows with the following features:

  SepalLengthCm: Sepal length in cm
  
  SepalWidthCm: Sepal width in cm
  
  PetalLengthCm: Petal length in cm
  
  PetalWidthCm: Petal width in cm

  Species: Target variable (Iris-setosa, Iris-versicolor, Iris-virginica)

  # Model Highlights:
  Algorithm Used: Logistic Regression

  Performance Metrics:
 
  Accuracy
       
  Confusion Matrix
       
  Classification Report

  Key Visualizations:
  
  Class distribution
       
  Pairplot of features
       
  Confusion matrix heatmap

  # Notes for Evaluators
  --> The file path in the code is set relative to the repository structure for portability.
      If running in Google Colab, ensure the dataset (Iris.csv) is uploaded manually to the Colab environment.
      Feel free to explore, run, and modify the code! 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Task 2: 

Unemployment Analysis

# Task Overview:

--> This project focuses on analyzing unemployment trends in India using Python. The goal is to gain insights into the unemployment rates by visualizing and 
    interpreting the provided data. This analysis will help understand the impact of unemployment in various regions of the country.

The dataset used in this project contains information about unemployment rates across different states in India, categorized by regions. It also includes dates and other relevant economic factors.

# Objectives:

Data Cleaning: Handle missing values and ensure the dataset is ready for analysis.

Exploratory Data Analysis (EDA): Generate insights through visualizations, such as line plots, bar charts, and heatmaps.

Regional Comparison: Analyze unemployment rates across different regions of India.

Time Series Analysis: Study the trend of unemployment over time.

# Project Structure:

Task_2_Unemployment_Analysis/

├── data/

│   └── Unemployment_in_India.csv  # Original dataset

├── outputs/

│   └── Data_recorded.png

│   └── cleaned_unemployment_data.csv  # Cleaned dataset saved by the script

├── src/

│   └── unemployment_analysis_jupyter.py

│   └── unemployment_analysis_py.py  # Python script for analysis

├── visualizations/

│   └── Corelation_heatmap.png

│   └── Distribution_UR.png

│   └── Regional_rates.png

│   └── Unemployment_rate.png

├── requirements.txt                # Dependencies
             

# Installation:

Prerequisites:

Make sure you have Python 3.7 or later installed. The required libraries are listed in the requirements.txt file.

# Steps to Install:

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
cd Task_2_Unemployment_Analysis

Install the dependencies:

pip install -r requirements.txt

# Usage:

Run the analysis script:

python src/unemployment_analysis.py

This will:

Clean the dataset.

Perform EDA and save the visualizations.

Save the cleaned dataset to the outputs/ folder.

# Access the results:

View the generated visualizations in the visualizations/ folder.

The cleaned dataset can be found in the outputs/ folder.

# Dataset:

The dataset used for this project is included in the data/ folder:

File: Unemployment_in_India.csv

Description: Contains unemployment data across different regions in India, along with dates and other economic indicators.

# Key Visualizations:

Unemployment Trends Over Time:

Line charts to observe how unemployment rates have changed over the years.

Regional Comparison:

Bar charts and heatmaps to compare unemployment rates across different regions.

Correlation Analysis:

Heatmaps to identify relationships between various economic factors.

# Requirements:

The following Python libraries are required for this project:

pandas
numpy
matplotlib
seaborn

# Install them by running:

pip install -r requirements.txt

# Results and Insights:

The analysis revealed significant variations in unemployment rates across regions.

Time series analysis identified trends and periods of high unemployment.

The visualizations provided clear insights into the data, highlighting the most affected regions.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Task 3: 

Car Price Prediction using Machine Learning

# Task Overview:
--> This project predicts the selling price of used cars based on various features such as mileage, fuel type, car age, and more. It utilizes a Linear Regression 
    model, trained on a dataset of used cars, to generate price predictions.

# Project Structure:

car-price-prediction/

│
├── data/

│   └── car_data.csv                # Dataset used for training

├── outputs                         # Outputs(Screen)

│   └── choice_1.png  

│   └── choice_2.png  


├── src                             # Main Python script (training + prediction)

│   └── car_prediction_jupyter.ipynb 

│   └── car_prediction_py.py  

└── requirements.txt                # Dependencies for the project

# Features Used in the Model:

The model uses the following features for prediction:

Present_Price: The current price of the car (in lakhs).

Kms_Driven: Total kilometers driven by the car.

Owner: Number of previous owners (0 for no previous owner, 1 for one owner, etc.).

Age: The age of the car (calculated as 2023 - Year of Purchase).

Fuel_Type: Whether the car runs on Petrol or Diesel.

Seller_Type: Dealer or Individual seller.

Transmission: Manual or Automatic transmission.

# Steps to Run the Project:

1. Clone the Repository

Clone this project to your local machine:

git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction

2. Install Dependencies

Install the required Python libraries using the following command:

pip install -r requirements.txt

3. Dataset

Ensure the dataset (car_data.csv) is located in the data/ folder. If you don't have the dataset, upload it or modify the path in main.py.

4. Train the Model

Run the following command to train the model:
python main.py

*When prompted*:

*Select 1* to train the model.

The trained model will be saved as models/linear_regression_model.pkl.

5. Predict Car Prices

Run the same main.py script to predict car prices:
python main.py

*When prompted*:

*Select 2* for car price prediction.

Enter details such as year of purchase, present price, mileage, fuel type, etc., as prompted.

The predicted car price will be displayed.

# Example Usage:

# Training the Model

Run the script:
python main.py

*Select 1* to train the model. 

Example output:

Training the model...

Model trained and saved at: models/linear_regression_model.pkl

# Predicting Car Prices

Run the script:
python main.py

*Select 2* to predict car prices. Enter details as prompted, 

for example:

Enter the year of purchase (e.g., 2015): 2018

Enter the present price (in lakhs, e.g., 6.5): 5.5

Enter the kilometers driven (e.g., 50000): 30000

Enter the fuel type (Petrol/Diesel): Petrol

Enter the seller type (Dealer/Individual): Dealer

Enter the transmission type (Manual/Automatic): Manual

Enter the number of previous owners (e.g., 0): 0

Estimated Selling Price: ₹3.15 Lakhs

# Dataset:

The dataset used in this project contains the following columns:

Car_Name: The name of the car.

Year: The year the car was purchased.

Present_Price: The current ex-showroom price of the car.

Kms_Driven: Total kilometers driven by the car.

Fuel_Type: Type of fuel (Petrol/Diesel).

Seller_Type: Whether the car is being sold by a Dealer or an Individual.

Transmission: Type of transmission (Manual/Automatic).

Owner: Number of previous owners.

Selling_Price: The price at which the car was sold (target variable).

# Technologies Used:

Programming Language: 

Python

Libraries:

pandas for data manipulation.

numpy for numerical operations.

scikit-learn for building the regression model.

pickle for saving and loading the trained model.

# Prerequisites:

Before running the project, ensure you have the following installed:

Python 3.8 or above

Libraries listed in requirements.txt (install using pip install -r requirements.txt).

# Future Enhancements:

(1) Add support for additional regression models such as Random Forest or Gradient Boosting.

(2) Create a user-friendly web interface using Flask or Streamlit.

(3) Expand the dataset with more features and records for better accuracy.

