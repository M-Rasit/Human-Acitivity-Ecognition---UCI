Hello :wave:

In this repository, I worked on [Human Activity Recognition with Smartphones](https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones) dataset from Kaggle. For the machine learning, I used both sklearn and H2O.

In the dataset, the experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKINGUPSTAIRS, WALKINGDOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

For the data analysis, magnitude columns can seperate static and dynamic activities. 
![magnitude](https://github.com/M-Rasit/Human-Activity-Recognition-UCI/blob/main/images/magnitude.png?raw=true)

For creating classification models, I used Logistic Regression, XGBoost Classifier, Random Forest Classifier, Decision Tree Classifier, Support Vector Classifier. Also, for the dimensionality reduction, I used PCA method on dataset and created models with the same Classifiers. In addition I used GridSearchCV for best parameters and evaluated their cross validation scores.

![pca](https://github.com/M-Rasit/Human-Activity-Recognition-UCI/blob/main/images/pca.png?raw=true)

![model_comparison](https://github.com/M-Rasit/Human-Activity-Recognition-UCI/blob/main/images/model_comparison.png?raw=true)

Thank you:tulip:
