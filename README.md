# Customer Churn Prediction with Ensemble Methods and Clustering

This project focuses on predicting customer churn in a telecom company using ensemble learning techniques and customer segmentation through clustering.

## Project Overview

The project aims to develop a robust churn prediction model by leveraging the power of ensemble methods and gain deeper insights into customer behavior through clustering.

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

- `notebook.ipynb`: Jupyter notebook containing the complete code and analysis.
- `data/`: Directory to store the dataset (not included in the repository).
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

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
