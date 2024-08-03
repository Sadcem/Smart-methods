# Titanic Machine Learning

## This project aims to introduce the most important steps of data analysis and explore the different stages. We will use the data of Titanic survivors available on the Kaggle website at the following link: https://www.kaggle.com/competitions/titanic/overview You can download the dataset and explore all the information about it in the following link: https://www.kaggle.com/competitions/titanic/data



### - First we will start with importing the dependencies, and reading the data available, then reviewing the data

![Screenshot 2024-08-03 122844](https://github.com/user-attachments/assets/d7c60584-e577-4f02-b9d9-41126b405df3)


### - Date preprocessing with ```  data.info() ``` command, provides a concise summary of the DataFrame's structure and content. It's a valuable tool for exploratory data analysis, helping you understand the data before diving deeper.

![Screenshot 2024-08-03 123526](https://github.com/user-attachments/assets/7790b19e-84e9-41cb-bc40-73cf2f584ab3)

### - Dealing with Missing Data with the ``` data.isnull().sum() ``` command in Python, specifically within the Pandas library, is a powerful tool for identifying missing values within a dataset.

![Screenshot 2024-08-03 124812](https://github.com/user-attachments/assets/1789a3a0-a4c6-41bc-99fd-00dd02268892)


### - Fill the missing values in Age with the mean of Age column with ``` fillna ``` function. To fix the missing values in the "Age" column, you can fill them using the mean of the existing values. Then because there is a large number of missing values in the Cabin column, so we will drop this column from the dataset.
![Screenshot 2024-08-03 125004](https://github.com/user-attachments/assets/7e069f78-23a3-4f5f-a79f-4dfede5fa6b8)


### - This code calculates the mode of the "Embarked" column and fills any missing values with that mode.

![Screenshot 2024-08-03 125522](https://github.com/user-attachments/assets/90596e0c-4303-44ed-bcc1-edf07957e368)

### - Drop useless columns such as PassengerId and Name Columns from the dataset. The axis=1 argument indicates that columns are being dropped.

![Screenshot 2024-08-03 125711](https://github.com/user-attachments/assets/9e456c77-81c0-4fb0-b339-9106ea64b1e4)

### - Encode Categorical Columns

![Screenshot 2024-08-03 125902](https://github.com/user-attachments/assets/62561d99-f662-472a-a222-8e9d41ec458d)

### - Dealing with Duplicates

![Screenshot 2024-08-03 130045](https://github.com/user-attachments/assets/c2d4ec12-0d3c-48f7-a2e7-bb6fd5289fd3)

![Screenshot 2024-08-03 130053](https://github.com/user-attachments/assets/408b2543-12b5-4c54-9aae-31fd16539dec)

### - Data Analysis
``` describe() ``` provides summary statistics for numerical columns, including count, mean, standard deviation, min, max, and quartiles. This function helps us understand the distribution and central tendencies of the data. However, in our Titanic dataset, while useful, it may not be the primary focus since many insights come from categorical features and their relationships with survival, which are better explored through other means.

![Screenshot 2024-08-03 130210](https://github.com/user-attachments/assets/1cbfa3bd-7ec2-426e-8b76-11556533afcf)


### - To build and evaluate a machine learning model effectively, it's essential to split the dataset into training and testing sets. The training set is used to train the model, allowing it to learn patterns and relationships within the data. The testing set, on the other hand, is used to evaluate the model's performance on unseen data, ensuring it can generalize well to new instances. This split helps prevent overfitting and provides a reliable estimate of the model's predictive accuracy.

![Screenshot 2024-08-03 130453](https://github.com/user-attachments/assets/e60651a0-68ef-4f2d-8cb7-038afcc89ca7)

### - Model training is a crucial step in the machine learning where the algorithm learns from the training data to make predictions. Logistic Regression is a commonly used algorithm for binary classification tasks

![Screenshot 2024-08-03 130604](https://github.com/user-attachments/assets/5d4c1e05-64dc-4b9d-9778-3565b0f75e33)


### - Model evaluation is crucial in machine learning to assess the performance of a trained model on testing data. The accuracy score, a common evaluation metric, measures the proportion of correct predictions out of all predictions. This helps to gauge the model's effectiveness, ensure it generalizes well to new data, and guide further improvements.

![Screenshot 2024-08-03 130615](https://github.com/user-attachments/assets/19e9a150-bc55-4b6c-ad52-e84fd1c8ef3d)

