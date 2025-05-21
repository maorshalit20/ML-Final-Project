This project implements a complete regression pipeline to predict median house values using California housing data.

##  Project Flow

1. *Data Preprocessing*:
   - Loads and cleans the training and test datasets.
   - Drops non-numeric features and separates features (X) from target (y).

2. *Exploratory Data Analysis (EDA)*:
   - Plots histograms, scatter plots, pairplots, and correlation heatmaps to explore feature relationships and detect patterns or outliers.

3. *Modeling & Evaluation*:
   - Builds multiple regression pipelines using:
     - Linear Regression (raw + scaled)
     - Ridge Regression with SelectKBest
     - Lasso Regression
     - Random Forest Regressor
   - Uses GridSearchCV with 5-fold cross-validation to find optimal hyperparameters.
   - Evaluates models using R² scores and compares performance across models.

##  Output
- Final comparison table between all models based on cross-validated R² score.
- Visualization of data distributions and feature relationships.

##  Technologies Used
- Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

##  Team
Gilad B., Maor S., Mor A.

## Video Presentation 
https://www.youtube.com/watch?v=BC3fJ7bLiBA
