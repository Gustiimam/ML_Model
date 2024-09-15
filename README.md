# Machine Learning Insurance Prediction Project

This repository contains a machine learning model that predicts whether a potential customer will purchase car insurance based on several features such as gender, age, and vehicle history. The model uses a RandomForestClassifier and is trained on a dataset of customer information.

##Project Files

- **Machine_Learning_Model.ipynb: Contains the code for training the machine learning model, including data preprocessing, model training, and evaluation.
- **Machine_Learning_Model_Tester.ipynb: Contains the code for testing the trained model on new data inputs.
- **insurance_model.pkl: The trained machine learning model saved in pickle format.

##Features Used in the Model

- Gender
- Age
- Driving License
- Region Code
- Previously Insured
- Vehicle Age
- Vehicle Damage
- Annual Premium
- Policy Sales Channel
- Vintage
- Instructions
- Training the Model:

## Instruction

### Training the Model
1. Use Machine_Learning_Model.ipynb to preprocess the dataset and train the model.
2. The dataset used for training should be placed in the appropriate directory.

###Testing the Model:

1. Machine_Learning_Model_Tester.ipynb loads the trained model and applies it to new data.
2. Ensure that the model and encoders are available in the specified directories.

### Model Deployment:

- The model is saved using pickle, and the encoders for categorical variables are also saved separately for future use.

## Setup

This project is designed to run on Google Colab, where Google Drive is mounted to store and load files.
Update the paths to the appropriate local or cloud storage locations if running outside of Colab.

## Prerequisites
Make sure you have the following installed:
- Python 3.x
- Required libraries:
- pandas
- numpy
- scikit-learn
- pickle

## How to Run
1. Clone the repository
2. Open the .ipynb files in Google Colab or Jupyter Notebook
3. Train the model using Machine_Learning_Model.ipynb
4. Test the model using Machine_Learning_Model_Tester.ipynb
