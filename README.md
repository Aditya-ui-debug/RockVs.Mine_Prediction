
# Rock vs mine prediction using python 

Usually, mines are mistaken as rocks during their identification, as mines can have the same shape, length, and width as rocks. To avoid this confusion it is better to use a more accurate input to receive an accurate output. One of the methods in detecting the mines is SONAR.. Sonar signals are used to record the various frequencies of underwater objects at 60 different angles. We constructed four classifier models according to their accuracy. Then, prediction models are used to predict the mine and rock categories. Python and Supervised Machine Learning Classification algorithms are used to construct these prediction models.




## Working procedure
working procedure:
Step 1: We gather the dataset and perform data preparation and Exploratory Data Analysis to clean the dataset.
 
Step 2: We split the data into train and test datasets. Using them we evaluate the classification models.
Step 3: Following the evaluation, the top three performing models are determined to be KNN, Random forest,Logistic regression,and SGD classifier

Step 4: The accuracy of these models is evaluated, and a classification report is generated.

Step 5: We now fit the models to create a prediction system that's both accurate and emcient.
Step 6: Using the predictive systems, we can finally determine if the object is a Mine or a Rock

## Final result/accuracy
KNN is most accurate in this project it gives 90.47% accuracy(0.9047619047619048)on the given dataset
