# INFO7390-Project-ML-Twitter-Sentiment-Analysis
- Import the required Python libaries at one place
- Place the train and test data files in the same folder as that of the notebook
- Read the train and test data set
- Perform Exploratory Data Analysis(EDA) and cleansing on the merge(train + test) tweets
- Perform Stemming and Tokenziation on the cleaned tweets using NLTK 
- Create features for Bag of words, TF-IDF, Word to Vector and Document to Vector using Gensim model 
- Evaluate the below mentioned classification model on the basis of high F1- Score:
	1. Logistic Regression
	2. Naive Bayes
	3. Support Vector Machine
	4. RandomForest (tree based algorithm)
	5. XGBoost (tree based algorithm)
	
- Hyper Parameters Tuning for the XGBoost model for params:
    1.  max_depth 
    2.  min_child_weight 
    3.  eta 
    4.  subsample 
    5.  colsample_bytree 
- Replace the parameter value of previous params before you tune next set of params
- Predict the values using the tuned model on the test sample shared.