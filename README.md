# Sleep Duration Among High School Students
## Machine learning (ML) for Predicting sleeping hours

### Background
Insufficient sleep among children and adolescents is associated with increased risk for obesity, diabetes, injuries, poor mental health, attention and behavior problems, and poor academic performance.
The American Academy of Sleep Medicine has recommended that, for optimal health, teens aged 13–18 years should sleep 8–10 hours per 24 hours. Thus, those who sleep less than 8 hours are considered having short sleep duration problem.
In the 2017 Youth Risk Behavior Survey (YRBS), a question about sleep duration in the questionnaire was answered by high school students in 38 states. 
#### Five models were used to analyze the dataset: linear regression, logistic regression, k-nearest neighbors, Naïve Bayes, and tree models.
#### We also apply 3-fold cross validation, variable selection approaches (backward, forward, and stepwise selection, and regularization regression methods (bagging, random forest, and boosting) to help us verify and tuning models. 

#### Step 1: attach the file
#### Step 2: clean the dataset.
run final-exploratory.ipynb. Data cleaning part is contained in this file.
#### Step 3: Run the ML methods.
run the final-linear.ipynb, final-logistic.ipynb, final-knn.ipynb, final-Naive bayes.ipynb, final-tree models.ipynb
For the person-level modeling, run the person_model_lasso.ipynb, person_model_rf.ipynb, person_model_xgb.ipynb
#### Step 4: Model tuning. 
run the final-model tuning.ipynb to tune the models.
