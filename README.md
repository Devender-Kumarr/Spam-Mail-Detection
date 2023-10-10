# Spam-Mail-Detection

## Overview

This project focuses on building a Spam Mail Detection system using machine learning techniques. It aims to classify emails into two categories: "ham" (non-spam) and "spam" based on their content. The project utilizes the scikit-learn library in Python to create a logistic regression model for classification.

## Project Structure

The project consists of the following components:

1. **Data Preparation**:
   - Importing necessary libraries, including Pandas and NumPy.
   - Reading the email dataset from a CSV file.
   - Data preprocessing, which involves dropping unnecessary columns and renaming columns for clarity.
   - Mapping labels "ham" and "spam" to numerical values (0 and 1) for classification.

2. **Feature Extraction**:
   - Tokenizing the email content.
   - Hashing symbols into a feature vector.
   - Creating a feature vector with zeros and ones to represent the presence of specific words or symbols.

3. **Data Splitting**:
   - Splitting the dataset into training and testing sets using scikit-learn's `train_test_split` function.

4. **Model Building**:
   - Utilizing scikit-learn's logistic regression model for binary classification.
   - Training the model on the training data.

5. **Model Evaluation**:
   - Predicting labels for the testing data.
   - Evaluating the model's performance using accuracy metrics.
   - Displaying training and validation accuracy.
 
 #Note: Ensure you have the email dataset in CSV format and specify the correct file path in the code,while running this code of your pc.

