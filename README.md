# Laptop-Price-Predictor--ML-Project

The goal of the project is to predict laptop prices using features like:
 1 Company          
 2   TypeName          
 3   Inches          
 4   ScreenResolution  
 5   Cpu               
 6   Ram               
 7   Memory           
 8   Gpu               
 9   OpSys             
 10  Weight           
 11  Price  
etc.

By training multiple regression models and comparing their performances, we aim to find the most accurate model for laptop price prediction.

## Models Used
We experimented with the following machine learning algorithms:
Algorithm	Description
Linear Regression	
K-Nearest Neighbors (KNN)	
Decision Tree Regressor	
Support Vector Regressor (SVR)	
Random Forest Regressor	
AdaBoost Regressor	
XGBoost Regressor
Gradient Boosting Regressor	
Voting Regressor

## Evaluation Metrics
We used the following metrics to evaluate model performance:

R² Score: Measures how well the model's predictions approximate the actual data points (closer to 1 is better).

Mean Absolute Error (MAE): Measures the average absolute difference between predicted and actual values (lower is better).

### How to Run
Clone the repository
Install dependencies.
run training script.
Evaluate Model.
Run the prediction app(not deployed)

### Future Enhancements
Hyperparameter tuning using GridSearchCV / RandomizedSearchCV.

Deploy the best model as a web application using Streamlit or Flask.

Add feature selection to reduce model complexity.

Use deep learning models (ANNs) for even better predictions
