# Habitable Exoplanet Recommendation System Using Random Forest Classifier

## Overview
This project focuses on developing a **Habitable Exoplanet Recommendation System** using **Random Forest Classifier**. The system analyzes data from NASA's Kepler mission to identify potentially habitable exoplanets based on various physical and environmental attributes. The project integrates **machine learning techniques** with **astrophysical research** to provide actionable insights into exoplanet habitability.

## Features
- **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales numerical features.
- **Exploratory Data Analysis (EDA)**: Visualizes key characteristics of the dataset using plots and graphs.
- **Machine Learning Models**: Implements Logistic Regression, Random Forest, SVM, and Gradient Boosting for classification.
- **Hyperparameter Tuning**: Optimizes the Random Forest model using GridSearchCV.
- **Recommendation Engine**: Recommends the top 10 potentially habitable exoplanets based on predefined criteria.
- **Feature Importance Analysis**: Identifies the most influential features contributing to habitability predictions.

## Dataset
The dataset used in this project is sourced from NASA's Kepler mission and is included in the repository as `exoplanets.csv`. It contains key attributes such as:
- **Planetary Radius (koi_prad)**
- **Equilibrium Temperature (koi_teq)**
- **Orbital Period (koi_period)**
- **Stellar Parameters (koi_steff, koi_srad, etc.)**
- **Disposition (koi_disposition)**: Indicates whether the exoplanet is a "False Positive", "Candidate", or "Confirmed".

## Project Workflow
1. **Data Preprocessing**:
   - Handle missing values by dropping or imputing them.
   - Encode categorical variables using `LabelEncoder`.
   - Scale numerical features using `StandardScaler`.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize distributions, scatter plots, and box plots to understand data behavior.

3. **Feature Selection**:
   - Select key features such as `koi_score`, `koi_prad`, and `koi_teq` for training.

4. **Model Training**:
   - Train multiple machine learning models and evaluate their performance.
   - Use Random Forest Classifier for its superior accuracy and robustness.

5. **Hyperparameter Tuning**:
   - Optimize the Random Forest model using GridSearchCV.

6. **Recommendation Engine**:
   - Recommend the top 10 habitable exoplanets based on habitability criteria.

7. **Visualization**:
   - Generate visualizations to interpret results and feature importance.

## Results
- The **Random Forest Classifier** achieved high accuracy in predicting exoplanet habitability.
- The system successfully recommended the top 10 potentially habitable exoplanets based on their **habitability scores**, **planetary radius**, **equilibrium temperature**, and **insolation flux**.
