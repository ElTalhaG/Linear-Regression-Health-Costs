# Linear Regression Health Costs Calculator

This project focuses on building a regression model to predict healthcare costs based on demographic and lifestyle features. The dataset includes information such as age, BMI, number of children, smoking status, and region. The goal is to train a model that accurately predicts healthcare expenses using a neural network approach.

The process begins with loading and inspecting the dataset. This involves reading the data into a Pandas DataFrame, checking for missing values, and understanding the structure of the dataset. Once the data is understood, preprocessing steps are applied. Categorical features such as sex, smoker status, and region are converted into numerical values. Numerical features like age, BMI, and children are normalized to improve model performance. The dataset is then split into a training set and a testing set, with 80% used for training and 20% for testing.

The model is built using a neural network with two hidden layers. Each layer applies a rectified linear unit (ReLU) activation function to improve learning efficiency. The Adam optimizer is used to adjust the model’s weights during training. The model is trained over 100 epochs with a validation split of 20% to monitor its progress.

After training, the model is evaluated using the test dataset. The primary metric for evaluation is Mean Absolute Error (MAE), which measures how close the predicted healthcare expenses are to the actual values. The model successfully achieves an MAE within the desired threshold, demonstrating its ability to generalize well on unseen data. Additionally, a visualization is created to compare the predicted expenses against the actual values.
