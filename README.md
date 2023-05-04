# Prediction-Model

## Cervical cancer screening prediction using Python

Built a classifier for cervical cancer screening prediction using the Kaggle dataset (https://www.kaggle.com/datasets/loveall/cervical-cancer-risk-classification).

Performed BINARY CLASSIFICATION for each of the 4 target variables
individually namely Hinselmann, Schiller, Cytology and Biopsy using two classifiers: SVM and KNN.

## Steps Performed:

### Data Preprocessing

- Dealt with missing values
- Identified and removed the outliers
- Normalized the data

### Data Balancing

- Used SMOTE to balance the classes

### Feature Extraction

- Identified useful features and eliminated redundant features
- Reduced the dimensionality of data
- Used PCA to extract the principal components

### Classifier

- Used two classifiers for this task: SVM and KNN 
- Tested the results by tuning the hyperparameters for each classifier, e.g., regularizer weight for soft-margin in SVM and the value of k in KNN

### Evaluation

- Three evaluation metrics are used for each classifier: Accuracy, Precision and Recall
- Confusion matrix for each target variable is plotted

### Data Visualization

- Visualized the normalized data distribution using boxplot
- Identified correlated features using correlation heatmap
- Plotted the confusion matrix
- Used seaborn and matplotlib libraries for visualization.
