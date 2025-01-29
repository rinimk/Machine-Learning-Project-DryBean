**DRY BEANS-Machine Learning Classification Project**

Dry bean is one of the highest-produced crops in the world, Dry Bean faces an extreme genetic diverse species in their crops. The quality of the seed is influencing in production of crops. Consequently, the classification of the seeds has become the need of the hour for production as well as marketing in order to avail the agricultural principles of sustainable systems. This research aims to develop a method which helps to obtain even varieties of seeds from the production of crops.

Multiclass classification of dry beans using the features such as form, shape, type, and structure by the market situation.To distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification.

Main objective is to perform exploratory data analysis (EDA) to understand the dataset. Train and evaluate classification models to classify seeds to 7 different categories. Interpret the results and assess feature importance.

This analysis focuses on the Drybean dataset, where the 'class' is the target variable.

**Dataset Information**

Seven different types of dry beans were used in this research, taking into account the features such as form, shape, type, and structure by the market situation. A computer vision system was developed to distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification. For the classification model, images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. Bean images obtained by computer vision system were subjected to segmentation and feature extraction stages, and a total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains.

**Class Labels**

Seker, Barbunya, Bombay, Cali, Derman, Horoz and Sira
There are no missing values and duplicates in the dataset
Outliers in  numerical features  are detected using the (IQR) method. Outliers are handled by capping based on lower and upper bounds
5 types of visualiztions  are done to explore relation between features
In this project there is only one categorical  column and all others are numerical.The only categorical column is 'Class' and that is the target varible in this project.Using label encoding it is encoded.The 7 types of classes are encoded to 0,1,2,3,4,5,6
Feature selection is done using SelectKBest Method.Based on the feature score out of 16 features only 15 are selected

**Model Building**

In this project 5 training models were used for performance evaluation. The models are:Logistic Regression,Support Vector Classifier,Decision Tree Classifier,Random Forest,Gradient Boosting
After Model Evaluation using metrics such as Accuracy, Precision, Recall, and F1 Score, the Support Vector Classifier emerged as the best-performing model based on its highest accuracy score.


Classification Report: A detailed breakdown of the model’s performance for each class, including metrics like precision, recall, and F1 score. 
Hyperparameter tuning is used to improve model performance. 
