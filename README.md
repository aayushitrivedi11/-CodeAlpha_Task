# CodeAlpha_Task

1. Iris Flower Classification
   
The Iris Flower Classification project involves developing a machine learning model to classify Iris flowers into three species—Setosa, Versicolor, and Virginica— 
based on their sepal and petal measurements (Sepal Length, Sepal Width, Petal Length, Petal Width) from the provided Iris.csv dataset. The project begins with data 
exploration, including numerical outlier detection using the IQR method and visualization through box plots, histograms, and pair plots to understand feature distributions and class separability. Outliers, primarily in SepalWidthCm for Iris-setosa and Iris-virginica, are identified but retained due to their natural 
occurrence in this clean dataset. The K-Nearest Neighbors (KNN) algorithm, with k=5, is used for classification after scaling features to ensure accurate distance calculations. The data is split into 80% training and 20% testing sets, achieving an accuracy of approximately 95–97%. Visualizations like the confusion matrix and a classification report confirm strong performance, with minimal misclassifications between Versicolor and Virginica. A sample prediction correctly classifies a new input as Iris-setosa, demonstrating the model’s effectiveness.

2. Unemployment Analysis with Python
   
This project analyzed the `Unemployment in India.csv` dataset to assess COVID-19's impact on unemployment rates across Indian regions from May 2019 to June 2020, using Python tools like pandas, matplotlib, and seaborn. After cleaning the data (removing 28 missing rows, standardizing columns, and converting dates), EDA and visualizations revealed a sharp unemployment spike during the April-May 2020 lockdown, with Puducherry (Urban: 76.74%) and Jharkhand (Urban: 70.17%) most affected, and urban areas (19.28% Post-COVID) hit harder than rural (16.18%). Recovery by June 2020 varied—Andhra Pradesh (Rural: 0.85%) recovered well, while Haryana (Rural: 35.57%) struggled. Insights highlight urban vulnerability, regional disparities (e.g., Tripura at 29.53% Urban), and agricultural resilience, suggesting targeted urban recovery and rural development.

3. Car Price Prediction with Machine Learning

This project builds a car price prediction model using a dataset (car data.csv) containing features like car name, year, selling price, present price, kilometers driven, fuel type, selling type, transmission, and owner count. The process involves loading and inspecting the data, preprocessing by creating a Car_Age feature and encoding categorical variables (Fuel_Type, Selling_type, Transmission) with one-hot encoding, and dropping irrelevant columns like Car_Name. Numerical features are standardized using StandardScaler to ensure consistent scaling. A RandomForestRegressor is trained on 80% of the data, with the remaining 20% used for testing, and evaluated using metrics like Mean Absolute Error, Mean Squared Error, and R² score. The model predicts the Selling_Price of cars, demonstrated with a sample prediction, achieving robust performance by leveraging features like car age and mileage.
   
