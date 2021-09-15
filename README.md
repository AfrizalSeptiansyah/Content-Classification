# Project Title

Content Classification Logistic Regression 

## Description

In this project, I will classify content into 5 categories: football, news, business, technology and automotive (imbalanced case). Using logistic regression with tfidf as feature extraction.

## Step By Step Solve Problem 
### 1. Label Distribution 
It seems that this is an imbalanced case so I use the metrics f1 score. I use class weight to fix it. 

### 2. Create Stopwords 
I use the bag of words to get the words that occur most often. I choose the 500 most frequently occurring words and then I selected the most frequently occurring words and not keywords.

### 3. Cleansing  
At this stage I tokenize, change all words to lowercase, take words that are more than 1 letter and remove stopwords and punctuation. 

### 4. Modeling 
I use tfidf as feature extraction and logistic regression algorithm. Then use RandomSearchCV with 5 cross-validations to find optimal hyperparameters.

### 5. Evaluation 

#### Classification Report


#### Confusion Matrix 

## Sanity Check 


# Conclusion 


