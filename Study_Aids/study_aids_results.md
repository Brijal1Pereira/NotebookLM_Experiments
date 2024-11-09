
Azure Machine Learning for Taxi Fare Prediction: FAQ
1. What is the purpose of this Azure Machine Learning tutorial?
This tutorial demonstrates how to use Azure Machine Learning Studio to predict taxi fares in New York City. You will learn how to import and explore data, run an automated machine learning pipeline, evaluate models, and select the best performing predictive model.

2. What is Azure Machine Learning Studio?
Azure Machine Learning Studio is a cloud-based platform for building, training, and deploying machine learning models. It offers both code-first and no-code/low-code environments, making it accessible to beginners and experienced data scientists. AzureML Studio provides tools for data import, exploration, pre-processing, model building, training, evaluation, and deployment as web services.

3. What is Automated Machine Learning (AutoML)?
Automated Machine Learning (AutoML) simplifies the process of building machine learning models by automating tasks such as model selection, hyperparameter tuning, and feature engineering. AutoML evaluates multiple algorithms, generates models, and compares their performance based on defined metrics to select the best model for the task. AutoML supports various machine learning tasks, including classification, regression, and forecasting.

4. What dataset is used in this tutorial?
The tutorial uses the "NYC-Taxi_Fare_Training_Dataset" which contains information about taxi trips in New York City. The goal is to predict the "fare_amount" based on other trip parameters.

5. How do I select specific models for AutoML to evaluate?
You can specify the models you want AutoML to use. In the "View additional configuration settings" section, untick "Use all supported models" and choose your desired models from the "Allowed models" dropdown menu. This tutorial specifically uses LassoLars, LightGBM, and XGBoostRegressor.

6. What is the purpose of splitting the data into training and testing sets?
Splitting the data allows you to train the model on a portion of the data (training set) and then evaluate its performance on unseen data (test set). This helps assess how well the model generalizes to new data and prevents overfitting.

7. Where can I find the performance metrics of the trained models?
You can view the performance metrics of the trained models in the "Models + child jobs" tab. The models are sorted by error, with the best-performing model at the top. Click on "View explanation" for a detailed breakdown of a model's performance and the "metrics section" for a comprehensive list of calculated metrics.

8. What is an Azure Compute Cluster, and why is it used in this tutorial?
An Azure Compute Cluster provides scalable, cloud-based resources for running machine learning training jobs. Clusters can scale up or down based on workload demands, allowing efficient parallel training of multiple models or handling large datasets. This tutorial utilizes the "BUS5WB-Compute-Cluster" for running the training jobs.
