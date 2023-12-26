# Diabetes-Prediction
1. Data Overview:
The dataset consists of 768 entries and 9 columns.
Features include Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, and Outcome.
There are no missing values in the dataset.
2. Data Visualization:
The correlation matrix heatmap indicates relationships between different features.
The count plot of the outcome variable shows a reasonably balanced distribution.
Histograms and pair plots provide insights into the distribution of individual features and their relationships with the outcome.
3. BMI Analysis:
A new column, 'BMI_measure,' is created to categorize BMI values into different groups (underweight, healthy, overweight, obese).
Visualization of BMI categories with respect to the outcome shows patterns in diabetes occurrence based on BMI.
4. Feature Analysis:
Visualizations explore the relationship between BMI, Blood Pressure, Age, Glucose, and the outcome.
Bar plots show the distribution of diabetes results based on BMI categories.
5. Data Cleaning:
The dataset is checked for zero values, and their percentages are calculated for different features.
Zero values are replaced with the mean values of the respective features.
6. Outlier Detection:
Distribution plots and box plots are used to detect outliers in the data.
Feature-wise box plots help visualize outliers in individual columns.
7. Model Building:
The k-nearest neighbors (KNN) algorithm is chosen for model building.
The optimal number of neighbors is determined using a plot of accuracy values for different values of k.
8. Model Evaluation:
The KNN model achieves an accuracy of approximately 81.82% on the test set.
Confusion matrix and classification report provide detailed information on model performance.
9. Key Takeaways:
The distribution of certain features (e.g., Glucose, BMI) differs significantly between diabetic and non-diabetic individuals.
BMI, Blood Pressure, and Age appear to be important factors in predicting diabetes.
