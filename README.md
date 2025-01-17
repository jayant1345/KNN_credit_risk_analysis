# KNN Credit Risk Analysis

## Project Overview

This project focuses on assessing the credit risk of loan applicants using the K-Nearest Neighbors (KNN) algorithm. By analyzing features such as age, total work experience, years in the current city, and cost-to-request ratio, the model classifies applicants into different risk categories. The primary objective is to develop a reliable model that aids financial institutions in making informed lending decisions.

## Table of Contents

- [Dataset](#dataset)
- [Data Exploration and Pre-processing](#data-exploration-and-pre-processing)
- [Model Development](#model-development)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Conclusion](#conclusion)
- [References](#references)

## Dataset

The dataset comprises various attributes of loan applicants, including:

- **Age**: Applicant's age
- **Total Work Experience**: Number of years the applicant has worked
- **Years in City**: Duration of residence in the current city
- **Cost to Request Ratio**: Financial metric indicating the ratio between the cost incurred and the amount requested
- **Cibil Score**: Credit score of the applicant
- **Total Bounces Past 12 Months**: Number of payment bounces in the past year

The target variable is the **Risk Segmentation**, which classifies applicants into different risk levels.

## Data Exploration and Pre-processing

Initial steps involve:

1. **Loading the Dataset**: Importing the data for analysis.
2. **Handling Missing Values**: Identifying and imputing or removing null values.
3. **Statistical Summary**: Generating descriptive statistics to understand data distribution.
4. **Visualizations**:
   - **Scatter Plot**: Relationship between Age and Total Work Experience.
   - **Box Plots**: Distribution of Age and Cibil Score to detect outliers.
5. **Feature Selection**: Identifying relevant features for the model.
6. **Data Transformation**: Normalizing or standardizing features to improve model performance.

## Model Development

Steps to build the KNN model:

1. **Data Splitting**: Dividing the dataset into training and testing sets.
2. **Model Training**: Applying the KNN algorithm to the training data.
3. **Hyperparameter Tuning**: Optimizing the number of neighbors (k) for best performance.
4. **Cross-Validation**: Ensuring the model's robustness and generalizability.

## Evaluation Metrics

The model's performance is evaluated using:

- **Accuracy**: Proportion of correctly classified instances.
- **Precision**: Accuracy of positive predictions.
- **Recall**: Ability to identify all positive instances.
- **F1 Score**: Harmonic mean of precision and recall.

## Results

The optimized KNN model achieved:

- **Accuracy**: *e.g.,* 85%
- **Precision**: *e.g.,* 80%
- **Recall**: *e.g.,* 78%
- **F1 Score**: *e.g.,* 79%

*Note: Replace the placeholder values with actual results from your model.*

## Conclusion

The KNN-based credit risk assessment model demonstrates the potential of machine learning in evaluating loan applicants. By effectively preprocessing data and tuning the model, financial institutions can leverage such tools to enhance decision-making processes.

## References

- [Credit Risk Analysis using KNN Model](https://www.kaggle.com/code/ardhikamalhaq/credit-risk-analysis-using-knn-model)
- [Credit Risk Assessment in R with KNN](https://medium.com/@charlesdirenzo/credit-risk-assessment-in-r-with-knn-53c0ad06ecf7)


