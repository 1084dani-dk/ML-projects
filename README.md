--------------------------------📌 Task 1 — Iris Dataset EDA & Visualization-------------------------------------

Objective: 
Explore the Iris dataset, visualize features, and understand distributions.

Dataset: Built-in Seaborn Iris dataset  
Columns: `sepal_length`, `sepal_width`, `petal_length`, `petal_width`, `species`  

Libraries: pandas, numpy, matplotlib, seaborn  

Steps Performed:
1. Import libraries
2. Load dataset
3. Basic overview: `head()`, `info()`, `describe()`, missing values
4. Visualizations:
   - Pairplot (feature relationships)
   - Correlation heatmap
   - Boxplot by species
   - Histograms of numerical features

Insights:
- 3 species: `setosa`, `versicolor`, `virginica`  
- Petal length & petal width strongly correlated  
- Outliers visible in boxplots

---

--------------------------------------📌 Task 2 — Stock Price Prediction-------------------------------------

Objective:  
Predict stock prices using historical data (Regression / Time Series).

Dataset: CSV (e.g., `stocks.csv`)  
**Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  

Steps Performed:
1. Load dataset
2. Explore data: `head()`, `describe()`, missing values
3. Visualize trends and moving averages
4. Train/test split
5. Train regression model (Linear Regression / other)
6. Evaluate performance: MSE, RMSE, R²

Insights:
- Trends, peaks, and dips identified
- Model predicts price trends with reasonable accuracy



-------------------------------------📌 Task 3 — Heart Disease Prediction------------------------------------

Objective:  
Predict heart disease using patient features (Binary Classification).

Dataset: `heart-disease.csv`  
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn  

Steps Performed:
1. Load dataset from Google Drive
2. Explore dataset (`shape`, `info`, `missing values`)
3. Visualize correlations and feature distributions
4. Train/test split
5. Train Logistic Regression model
6. Evaluate: accuracy, confusion matrix, classification report

Insights:
- Key features: `cp`, `thalach`, `oldpeak`  
- Logistic Regression accuracy ~80–88%  
- Confusion matrix shows True Positives & True Negatives
