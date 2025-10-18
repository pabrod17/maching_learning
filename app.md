# Machine Learning Project Documentation 🤖

## Table of Contents
- [Process Overview](#process-overview)
- [Required Libraries](#required-libraries)

## Process Overview

### 1. 📊 Import the Data
- Load datasets
- Initial data inspection

### 2. 🧹 Clean the Data
- Handle missing values
- Remove duplicates
- Format data types

### 3. ✂️ Split the Data
- Separate into Training/Test sets
- Validate data distribution

### 4. 🔨 Create a Model
- Select appropriate algorithm
- Define model architecture

### 5. 📈 Train the Model
- Fit model to training data
- Monitor learning process

### 6. 🎯 Make Predictions
- Test model on new data
- Generate predictions

### 7. 📝 Evaluate and Improve
- Measure performance metrics
- Optimize model parameters

## Required Libraries
| Library      | Purpose                    |
|--------------|----------------------------|
| Numpy        | Numerical computations     |
| Pandas       | Data manipulation          |
| MatPlotLib   | Data visualization         |
| Scikit-Learn | Machine learning algorithms|

## Install Anaconda 
(At the same time this is installed, Jupyter is installed as well)
## Commands
- Jupyter notebook
- localhost:8888/tree

## Importing a Data Set
- https://www.kaggle.com/
(https://www.kaggle.com/datasets/gregorut/videogamesales/data)
- username: Pabloqwert
- Move the .csv file to my folder and workspace

## HelloWorld2

### 1. 📊 Import the Data
- Download .csv -> https://www.dropbox.com/scl/fi/bieq5udd5w882xy9d86mt/music.csv?rlkey=jjis8mfxrkncgb71zt1dl6zsx&e=2&dl=0

### 2. 🧹 Clean the Data

### 3. ✂️ Split the Data
- (X) Input set -> Create new datagrame only with columns: age, gender
- (y) Output set -> Create new frame only with genre column values

### 4. 🔨 Create a Model (Using an algorithm)
- Algorithm -> decision tree
    - DecisionTreeClassifier
- These algorithms are already implemented in a library called -> sklearn.tree

### 5. 📈 Train the Model
- Fit input and output sets

### 6. 🎯 Make Predictions

### 7. 📝 Evaluate and Improve
- Measure and calculate Accuracy of a model
- Split our data set into two sets.
    - train_test_split:
    (This function always take randomly picks data for training and testing.
    Thats why, Score changes in each execution)
    - test_size=0.2 -> That means, the function use 20% of the data.
        - Training (70-80%)
        - Testing (20-30%)
- To calculate the accuracy:
    - accuracy_score:
        - Compare X_Test predictions with the actual 
        values we have in the outpout set y_test
    

## HelloWorld22

### Model persistence:
- In a real application we dont need to train model every time
- joblib:
    - to store our train model in a file

## HelloWorld222

### Visualizing a Decision Tree:
- Export our model in a visual format 

### 1. Shortcuts
- tab to check functions after dot (.)
- (below mayus) shift + tab (cursor on the function name)

- once in a while = de vez en cuando


