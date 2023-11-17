# CTR-Prediction
CTR prediction using Random Forest Classifier
This repository contains code for predicting click-through rates using a Random Forest Classifier. The dataset used for training and testing is provided in the `train.csv` and `test.csv` files, respectively.
## Dataset
The dataset consists of various features related to online advertising, and the goal is to predict whether a user will click on an ad or not. The features include information such as the hour of the day, device type, site information, and more.
## Model Training
The Random Forest Classifier is employed for training the click-through rate prediction model. GridSearchCV is used to find the best hyperparameters for the model.
## Evaluation
The model's performance is evaluated using accuracy and precision scores on a test set.<br/>
My accuracy  is : 0.8394897124329566<br/>
My precision is : 0.5422661870503597<br/>
## Creating a Submission File
The trained model is used to make predictions on the test set, and the results are saved in a CSV file named submission.csv.
## Usage
1.Ensure you have the required Python libraries installed by running:<br/>
```pip install pandas scikit-learn```<br/>
2.Run the Jupyter notebook or Python script to train the model and generate predictions.<br/> 
3.View the evaluation metrics and the submission file.<br/>
##  Files Included
- train.csv: Training dataset.  
- test.csv: Testing dataset.  
- submission.csv: Final submission file.<br/><br/>
Feel free to explore and modify the code to suit your needs. If you have any questions or suggestions, please open an issue.
