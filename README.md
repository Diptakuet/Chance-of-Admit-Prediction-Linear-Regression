# Chance-of-Admit-Prediction-Linear-Regression
Chance of admit prediction using linear regression
In this project we're going to use information like a student's gpa, gre, toefl, university ranking, etc. to predict the chance of admit. This kind of model is useful for graduate and undergraduate students. The dataset for this problem is taken from https://www.kaggle.com/mohansacharya/graduate-admissions/download.

We will create a model with the following steps:

1. Download and explore the dataset
2. Prepare the dataset for training
3. Create a linear regression model
4. Train the model to fit the data
5. Make predictions using the trained model

# Datasets:
Dataset contains 400 rows and 9 columns.

The features in the dataset for prediction are-
1. Serial Number
2. GRE Score	
3. TOEFL Score	
4. University Rating	
5. SOP	
6. LOR	
7. CGPA	
8. Research

Our target is to predict the 'chance of admit'.

# Loss Function:
We have utilized l1_loss function to build our AdmissionModel.
By setting up hyperparameters we have been able to minimize validation loss upto 0.7411876916885376.
According to our understanding learning rate 1e-1, 1e-2 gives better performance. 
# Benefit of the model
The model is useful for any graduate or undergraduate student for predicting their chances of admission to a university prior to the application process.
As we know to get an admission, certain prerequisites need to be fulfilled, such as gre, toefl, gpa, etc. However, There are no any warranted score for each of those prerequisites to confirm an admission.Therefore, it is hard for a student to evaluate their profile and to get prepared accordingly. This model will provide students a scope for evaluating their profile and predict their chance of admission to a university.
# Future Scope
In future, we can extend this work to predict a best suitable university for a student based on their evaluated profile.
