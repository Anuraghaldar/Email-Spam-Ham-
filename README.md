# EMAIL SPAM HAM FILTERING 

![](https://mailbakery.s3.amazonaws.com/wp-content/uploads/2017/10/13130910/25_IMAGE-02.jpg)

## Project Description

The project focuses on creating a machine learning model to classify emails as either spam (unwanted or promotional messages) or ham (legitimate messages). This is crucial for improving email filtering systems, ensuring users receive only relevant and important messages in their inboxes.

## Detailed Steps


- **Importing Libraries:**
  - Import essential libraries required for the project, such as `Pandas` for data manipulation, `Numpy` for numerical operations, and `Scikit-learn` for machine learning algorithms and evaluation metrics.

- **Loading the Data:**
  - Load the email dataset [`email_spam_ham.csv`](https://github.com/Anuraghaldar/Email-Spam-Ham-/blob/main/email_spam_ham.csv) which typically contains email messages and their corresponding labels (spam or ham).

- **Data Exploration:**
  - Perform exploratory data analysis to understand the structure and distribution of the dataset. This includes checking the first few rows of the dataset, understanding the data types of each column, and analyzing the distribution of the target variable (spam or ham).

- **Data Preprocessing:**
  - Handle any missing values in the dataset.
  - Encode categorical variables, especially the target variable, to a format suitable for machine learning algorithms. For instance, convert labels like `"ham"` and `"spam"` into numerical values 0 and 1.

- **Splitting the Data:**
  - Divide the dataset into training and testing sets. The training set is used to train the model, while the testing set is used to evaluate its performance on unseen data.

- **Model Training:**
  
  - Choose an appropriate machine learning algorithm (e.g., Logistic Regression) and train the model on the training data.

- **Model Evaluation:**
  - Evaluate the model's performance on the testing set using appropriate metrics like accuracy. This helps in understanding how well the model generalizes to new, unseen data.

- **Performance Check:**
  - Evaluate the accuracy of the model by testing it on the testing set. This helps to ensure that the model performs well on unseen data.

- **Final Model and Prediction:**
  - Use the trained model to make predictions on new email data. This involves transforming new email text data into numerical features using the same method as before and then using the trained model to classify the emails as spam or ham.
