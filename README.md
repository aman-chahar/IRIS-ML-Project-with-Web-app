# IRIS Machine Learning Project with Streamlit web app
Python script for a basic machine learning project that involves loading the Iris dataset, training three different machine learning models (Logistic Regression, Decision Tree, and Random Forest), and then saving these models as pickle files, to predict the label on web app using streamlit.

Streamlit web app link:- https://iris-ml-project-with-web-app-wrfcvpt3eczzvyotx8vswn.streamlit.app/

1. **Import the Required Libraries**: In this section, I import the necessary libraries for your project, including Pandas for data preprocessing, NumPy for mathematical computations, and scikit-learn for machine learning models. I also import the `train_test_split` function for splitting your data and the `pickle` module for saving trained models.

2. **Load the Dataset**: load the Iris dataset from a CSV file into a Pandas DataFrame. Then display the first few rows of the dataset and check for its shape, missing values, and column names.

3. **Value Count for Target Variable - label**: Count the occurrences of each class in the 'label' column of your dataset, providing insights into the class distribution.

4. **Select the Dependent and Independent Features**: Separate the features (independent variables) and the target variable (dependent variable) by using DataFrame indexing.

5. **Split the Data into Train and Test Sets**: Split your dataset into training and testing sets using the `train_test_split` function. The training set contains 75% of the data, while the testing set contains 25%.

6. **Train the ML Model**: Create instances of three different machine learning models: Logistic Regression, Decision Tree, and Random Forest. You then fit these models to the training data using the `.fit()` method.

7. **Save the Trained ML Model**: Save each of the trained machine learning models in binary format using the `pickle` module, resulting in three pickle files: 'lr_model.pkl', 'dt_model.pkl', and 'rf_model.pkl'.

8. **Model Deployment**: The trained Machine Learning models are saved to pickle files for use in the Streamlit app. The Streamlit app is set up to run locally and deployed on a web server for public access. Streamlit app link is available on top.
