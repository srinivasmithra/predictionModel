# predictionModel
Disease prediction model to predict on target column of the sample dataset (from kaggle). It's is implemented with few ML prediction models such as logistic regression and K near neighbour.


Data source: https://www.kaggle.com/datasets/priyanka841/heart-disease-prediction-uci

I have tried working in few machine learning models:
1. LogisticRegression 
2. KNearNeighbour
3. RandomForestClassifier
4. Decision Tree(Not yet commited)
5. Naive Bayes(Not yet commited)


Parameters
There are a total of 14 columns, the columns are described as followed:

age
sex
chest pain type (4 values)
resting blood pressure
serum cholestoral in mg/dl
fasting blood sugar > 120 mg/dl
resting electrocardiographic results (values 0,1,2)
maximum heart rate achieved
exercise induced angina
oldpeak = ST depression induced by exercise relative to rest
the slope of the peak exercise ST segment
number of major vessels (0-3) colored by flourosopy
thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
target, i.e. whether the patient has heart diseases or not [0 for patient who has heart diseases & 1 for no heart diseases]

Steps Followed:
1. Download the data from source.
2. Read the csv file and made few changes to dataframe(fit and transform, splitting etc)
3. LogisticRegression model is loaded then later got predicted results with test values.
4. And then later model evalution with different score calculations (precision_score, auc_score etc).
5. Same flow from steps(3 and 4 ) followed for rest of the models.
6. At last, all 3 models are summerized.





