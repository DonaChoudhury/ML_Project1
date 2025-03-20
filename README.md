This project is aimed at detecting fraudulent credit card transactions using a machine learning model. The goal is to create an effective model that can distinguish between legitimate and fraudulent transactions.

**Project Overview**
Credit card fraud is a significant issue in the financial sector. Identifying fraudulent transactions is critical to prevent financial losses and ensure the safety of customers. The dataset used in this project contains anonymized credit card transactions, with features generated using PCA (Principal Component Analysis) and a binary class label indicating whether a transaction is legitimate (0) or fraudulent (1).

**Dataset**
-The dataset is present in a .zip file and contains credit card transactions 

-The dataset consists of:
 -Amount:-Transaction Amount
 -Class:-It consists of a binary label where 0 indicates a legitimate transaction and 1 denotes a fraudulent      transaction

**Project Structure**
1. Data Loading and exploration:
 Load the dataset into a Pandas DataFrame.
 Display sample rows and examine basic statistics and null values.
  
2. Data Preprocessing:
 Identify the number of legitimate vs fraudulent transactions.
 Calculate descriptive statistics and analyze average values by class.

3. Under-sampling:
 Balance the dataset by sampling an equal number of legitimate and fraudulent transactions.
 Create a new, balanced dataset.

4. Data Splitting:
 Separate features (X) and labels (Y).
 Split into training and testing sets with stratified sampling.

5. Model Training:
 Train a Logistic Regression model using the training set.

6. Model Evaluation:
 Evaluate performance with accuracy scores on training and test sets.
 Check for overfitting (high training accuracy) or underfitting (low training accuracy).

**Usage**
1. Open the file including the code in Google Colab(CreditcardF.ipynb) and click on connect(wait for it to get 
connected , once connected follow step-2).

2. For the steps 2-4 click on Runtime and select run all in order to run all the cells at once or the cells can be  ran individually by using Shift+Enter. 
  Load the dataset by uploading the dataset from the .zip file by clicking on files(present on left) and then click on upload file (wait for the file to get uploaded) and do the required  preprocessing using the provided code.

3. Train the model using Logistic Regression Model

4. Evaluate the model using accuracy scores and check for overfitting or underfitting

**Results**
The model's performance is evaluated using accuracy on both the training and testing datasets. The key evaluation metrics include:

Accuracy Score: Indicates the percentage of correctly classified transactions.
The goal is to achieve a good balance between sensitivity (detecting fraudulent transactions) and specificity (avoiding false positives).

