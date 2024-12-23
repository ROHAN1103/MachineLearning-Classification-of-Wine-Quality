# MachineLearning-Classification-of-Wine-Quality
  The Wine dataset is one of the datasets in machine learning and statistics, used for classification tasks. It contains information about Wine quality. Wine quality is determined by several factors or features and they are fixed acidity, volatile acidity,	citric acid,	residual sugar,	chlorides,	free sulfur dioxide,	total sulfur dioxide,	density,	pH,	sulphates,	alcohol and	quality. Here all the factors are in numeric data types. 
![DALL·E 2024-12-23 09 28 47 - A visually engaging and scientific representation of wine quality testing, featuring a bold heading 'Wine Quality Testing' at the top  The image inclu](https://github.com/user-attachments/assets/3448e212-4c8e-403d-818b-b45e95f8958a)
There are 1599 rows of data and the quality of the wine i.e., target attribute is a scaled value from 3 to 8. For the better classification the quality between 3 to 5 is considered as poor(mentioned as false) and from 6 to 8 is considered as Good(mentioned as True).

**Key Characteristics**
* Number of Rows (Samples): 1599
* Number of Columns (Features): 12
* Target Classes: 2 (actually 6 but grouped together to 2)
* Data Type: Numeric features and numeric target.

**Preprocessing and Exploratory data analysis(EDA)**

Preprocessing steps:
* Removing Unnecessary Columns
* Handling Missing Values
* Encoding Target Labels
* Feature Scaling

Exploratory Data Analysis:
* Analysis of dataset and Class Distribution.
* Correlation Analysis
* Histograms and scatter plots.

**ML Models used for Classification:**
1. Logistic Regression
2. Support Vector Classifier

**Metrics used for analyzing performance**
1. Accuracy_score
2. Percision_score
3. Recall_Score
4. Confusion_matrix

**Analysis**

  Initially model is trained with all the features, then it is trained by removing few features but the accuracy is not improved. Then the target attribute is reframed and the target variables is classified into true and false to improve the accuracy.
