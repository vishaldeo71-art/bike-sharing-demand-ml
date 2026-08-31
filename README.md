# bike-sharing-demand-ml
Machine Learning project using the Kaggle Bike Sharing Demand dataset
🚲 Bike Sharing Demand Prediction using Machine Learning
📌 Project Overview
This project uses Machine Learning techniques to predict bike rental demand using the Kaggle Bike Sharing Demand dataset.
The project analyzes how factors such as weather, temperature, humidity, season, working days, and time affect the total number of bike rentals.
Multiple Machine Learning regression models are trained and compared to identify the best-performing model.
📂 Dataset
The dataset used in this project is the Bike Sharing Demand dataset from Kaggle.
The dataset contains 10,886 records and 12 columns.
Some important features include:
datetime – Date and time of the observation
season – Season category
holiday – Whether the day is a holiday
workingday – Whether the day is a working day
weather – Weather condition
temp – Temperature
atemp – Feeling temperature
humidity – Humidity level
windspeed – Wind speed
casual – Number of casual users
registered – Number of registered users
count – Total bike rental demand (Target Variable)
🎯 Project Objective
The main objective of this project is to:
Analyze the Bike Sharing Demand dataset.
Perform data preprocessing and exploratory data analysis.
Create useful features from the datetime column.
Train multiple Machine Learning models.
Compare model performance using evaluation metrics.
Identify the best model for predicting bike rental demand.
⚙️ Machine Learning Models Used
The following regression models were implemented:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
K-Nearest Neighbors (KNN) Regressor
📊 Model Performance
The models were evaluated using the R² Score.
Model	R² Score
Linear Regression	0.3959
Decision Tree	0.8475
Random Forest	0.9546
KNN (K=3)	0.5841
🏆 Best Model
Random Forest Regressor achieved the highest R² score:
R² Score = 0.9546
This means that the Random Forest model explained approximately 95.46% of the variation in bike rental demand on the test data.
🔄 Project Workflow
Bike Sharing Demand Dataset
            ↓
Data Loading
            ↓
Data Cleaning
            ↓
Exploratory Data Analysis
            ↓
Feature Engineering
            ↓
Train-Test Split
            ↓
Model Training
            ↓
Model Evaluation
            ↓
Model Comparison
            ↓
Best Model Selection
📈 Evaluation Metrics
The models were evaluated using:
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
🛠️ Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
GitHub
📁 Project Structure
bike-sharing-demand-ml/
│
├── bike_sharing_ml_final.ipynb
├── README.md
└── train.csv
Note: If you did not upload train.csv to GitHub, remove it from the project structure.
🚀 How to Run the Project
Clone or download this repository.
Open the .ipynb notebook using Google Colab or Jupyter Notebook.
Install the required Python libraries if necessary.
Upload the train.csv dataset from Kaggle.
Run the notebook cells sequentially.
📌 Key Conclusion
Among all the models tested, Random Forest Regressor performed the best, achieving an R² score of 0.9546.
Author
Aaryan Srivastava
The results show that bike rental demand has complex and non-linear relationships with factors such as time, weather conditions, season, temperature, and working days. Random Forest was able to capture these relationships more effectively than the other models tested.
