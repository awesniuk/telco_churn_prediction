# Customer Churn Prediction with Ensemble Methods and Clustering

## Project Overview

This project focuses on predicting customer churn in a telecom company using ensemble learning techniques and customer segmentation through clustering.

Source dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Methodology

1. **Data Preprocessing:**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. **Ensemble Modeling:**
   - **Voting Classifier:** Combining predictions from Random Forest, Logistic Regression, and K-Nearest Neighbors.
   - **Hyperparameter Tuning:** Optimizing model parameters using GridSearchCV.
   - **Threshold Optimization:** Finding the optimal threshold for churn prediction based on tenure.

3. **Clustering:**
   - **K-means Clustering:** Segmenting customers based on relevant features.
   - **Elbow Method:** Determining the optimal number of clusters.
   - **Silhouette Analysis:** Evaluating cluster quality.
   - **Cluster Visualization:** Using PCA and 3D scatter plots to visualize customer segments.

## Results

- Achieved improved churn prediction accuracy using the ensemble model.
- Identified distinct customer segments with varying churn probabilities.
- Gained insights into the characteristics of high-risk churn segments.

## Files and Directories

- `telco.ipynb`: Colab notebook containing the complete code and analysis.
- `README.md`: This file.

## Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- plotly
- category_encoders
- imbalanced-learn

## Future Work

- Explore other ensemble methods like boosting algorithms.
- Develop strategies for targeted interventions based on cluster insights.
- Deploy the model for real-time churn prediction.
