# road_accident_risk_analysis_prediction_india_2022
## Project Title:  Road Traffic Accident Analysis, Risk Segmentation &amp; Prediction using ML models (India 2022). 

📌 **Project Overview:**

This project analyzes the Number of Cases Reported Due to Road Traffic Accidents in India during 2022 using Machine Learning techniques. The objective is to explore accident patterns across Indian States/UTs, identify high-risk regions through clustering, and build predictive models for accident-related outcomes.

The project combines:

Exploratory Data Analysis (EDA)

Data Preprocessing

Feature Engineering

Regression-based Prediction

Clustering-based Risk Segmentation

Model Evaluation and Comparison. 

🎯 **Objectives:**

Analyze accident trends across Indian States and Union Territories.

Identify regions with high accident severity and fatality rates.

Predict accident-related outcomes using Regression models.

Segment regions into risk groups using Clustering techniques.

Generate actionable insights for road safety and policy planning.

📂 **Dataset Information:**

### Source: Government of India Open Data Portal (data.gov.in)

Dataset: Number of Cases Reported Due to Road Traffic Accidents During 2022

**Features**
State/UT/City

Road Accidents - Cases

Road Accidents - Injured

Road Accidents - Died

Railway Accidents - Cases

Railway Accidents - Injured

Railway Accidents - Died

Railway Crossing Accidents - Cases

Railway Crossing Accidents - Injured

Railway Crossing Accidents - Died

Total Traffic Accidents - Cases

Total Traffic Accidents - Injured

Total Traffic Accidents - Died

🔧 **Data Preprocessing:**

The following preprocessing steps were performed:

Missing value analysis

Duplicate record removal

Column name cleaning and standardization

Label Encoding of State/UT/City

Feature Scaling using StandardScaler

Outlier analysis using Boxplots

Correlation analysis using Heatmaps. 

📊 **Exploratory Data Analysis (EDA):**

Several visualizations were created to understand the dataset:

Distribution of accident cases

Distribution of injuries and fatalities

State-wise accident comparison

Correlation Heatmap

Pair Plot Analysis

Histogram and Density Plots. 

Boxplots for Outlier Detection. 

Scatterplots for Injury vs Fatality Analysis. 

Cluster Visualizations using PCA. 

🤖 **Machine Learning Models Used:**

#### Regression Models

The following regression algorithms were implemented and compared:

Linear Regression

Ridge Regression

Random Forest Regressor

XGBoost Regressor

Extra Trees Regressor

**Regression Evaluation Metrics:**

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Cross Validation Score

**Additional Regression Analysis:**

Actual vs Predicted Plot

Residual Distribution Plot

Residual Scatter Plot

Prediction Error Plot

Feature Importance Analysis. 

📈 **Clustering Models Used:**
#### 1. K-Means Clustering

Used for identifying accident-risk groups among States/UTs.

**Techniques Used:**

Standard Scaling

Elbow Method

Silhouette Score

PCA-based Visualization. 

#### 2. Hierarchical Clustering

Used to identify hierarchical relationships among regions based on accident characteristics.

**Techniques Used:**

Agglomerative Clustering

Dendrogram Visualization

Cluster-wise Statistical Analysis. 

📋 **Project Workflow:**

Data Collection

Data Cleaning

Exploratory Data Analysis

Feature Engineering

Regression Model Building

Model Evaluation

Clustering Analysis

Risk Segmentation

Insight Generation

Documentation. 

📚 **Libraries Used:**

Data Manipulation

NumPy

Pandas

Visualization

Matplotlib

Seaborn

Plotly

Machine Learning

Scikit-Learn

XGBoost

Statistical Analysis

SciPy. 

🚀 **How to Run This Project:**

#### Option 1: Google Colab

Open the notebook (.ipynb file) in Google Colab.
Upload or mount the dataset from Google Drive.
Install any required packages if necessary:

```pip install xgboost```

Run notebook cells sequentially.
Open the .ipynb notebook.
Execute each cell using:

```Ctrl + Enter```

#### Option 2: Jupyter Notebook

Clone the repository:

```git clone <repository-url>```

Navigate to the project directory.
Launch Jupyter Notebook:
jupyter notebook
Open the .ipynb notebook.
Execute each cell using:

```Ctrl + Enter```

or

```Shift + Enter```

📊 **Key Outcomes:**

Identified high-risk accident regions across India.

Compared multiple regression models for predictive performance.

Segmented States/UTs into meaningful accident-risk clusters.

Generated data-driven insights for accident prevention and safety planning.

🔮 **Future Scope:** 

Incorporate multi-year accident datasets.

Build time-series forecasting models.

Develop interactive dashboards using Streamlit or Power BI.

Integrate geospatial visualizations using GIS tools.

Deploy the best-performing model as a web application.

👨‍💻 **Author**

#### Preetam Mukherjee

#### B.Tech (Mechanical Engineering)

#### BS Degree in Data Science and Applications

#### Machine Learning | Data Science | Artificial Intelligence | Data Analytics. 
