# human-activity-recognition
Human Acitivity Recognition (HAR) is a model that predicts human activities such as Walking, Walking_Upstairs, Walking_Downstairs, Sitting, Standing or Laying.

# Requirements
Python 3.8+ Jupyter Notebook - Kaggle Notebook is preferrable.

# Dataset
The Dataset : https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones

# How to Run The Notebook.
1. Login to Kaggle.com
2. Visit https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones
3. Click on "New Notebook" Option Available on the top of the screen.
4. Download the ".ipynb" File attached in the current repository, select the right version
5. Upload On the New Notebook place by clicking on Import Notebook option.
6. Run The Notebook program

# Run the program in virtual envrionment python
1. Create virtual environment
2. Activate virtual environment
3. Install requirements.txt 
4. Run jupyter notebook and Open the .ipynb notebook file on the localhost:8888
   
# Key Insight
1. Human activity recognition is the problem of classifying sequences of accelerometer data recorded by specialized harnesses or smartphones into known well-defined           movements.
2.Visualize the activity distribution using a countplot.
3.Examine the distribution of static and dynamic activities.
4. Fit and evaluate the performance of three machine learning models: SVM, Random Forest, and Logistic Regression.
    * SVC - Training Accuracy : 99.40 %  and Testing Accuracy : 96.33 %
    * RandomForest - Training Accuracy : 98.80 % and Testing Accuracy: 91.41 %
    * LogisticRegression - Training Accuracy : 99.37 % and Testing Accuracy : 96.13 %
5. The SVM model demonstrated superior performance in both fitting the model and predicting results.
6. The model excelled at accurately predicting activities such as walking, walking downstairs, and laying. However, it struggled to differentiate between similar activities like sitting and standing, indicating a high correlation between these movements.
