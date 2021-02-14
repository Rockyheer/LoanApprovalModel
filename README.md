# Loan Approval Prediction
Loan Approval Prediction in Python

In this project, we have used various EDA techniques and machine learning algorithms to predict the chances of loan approval using sci-kit libraries from python.

This project covers the complete process from data collection to deploying modelling and evaluation:

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Model Development and Evaluation


The flow of this project can be seen in the image below: 

![flow](https://github.com/heer77331/LoanApprovalModel/blob/master/flow.png?raw=true)

## Prerequisite
What things you need to install the software and how to install them:

1. Python 3.6
    * This setup requires that your machine has python 3.6 installed on it. you can refer to this url https://www.python.org/downloads/ to download python. Once you have python downloaded and installed, you will need to setup PATH variables (if you want to run python program directly, detail instructions are below in how to run software section). To do that check this: https://www.pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/.
    * Setting up PATH variable is optional as you can also run program without it and more instruction are given below on this topic.
2. Second and easier option is to download anaconda and use its anaconda prompt to run the commands. To install anaconda check this url https://www.anaconda.com/download/
3. You will also need to download and install below 3 packages after you install either python or anaconda from the steps above
    * Sklearn (scikit-learn)
    * numpy
    * scipy
 
If you have chosen to install python 3.6 then run below commands in command prompt/terminal to install these packages
pip install -U scikit-learn
pip install numpy
pip install scipy

If you have chosen to install anaconda then run below commands in anaconda prompt to install these packages
conda install -c scikit-learn
conda install -c anaconda numpy
conda install -c anaconda scipy

## Dataset used

The data source used for this project is analytics vidya which contains 2 files with .csv format for training and testing. Below is some description about the data files used for this project.

Dataset Description:

Loan_ID - Unique Loan ID

Gender - Male/ Female

Married- Applicant married (Y/N)

Dependents - Number of dependents

Education - Applicant Education (Graduate/ Under Graduate)

Self_Employed - Self employed (Y/N)

ApplicantIncome - Applicant income

CoapplicantIncome - Coapplicant income

LoanAmount - Loan amount in thousands

Loan_Amount_Term - Term of loan in months

Credit_History - credit history meets guidelines

Property_Area - Urban/ Semi Urban/ Rural

Loan_Status - Loan approved (Y/N)

## Future Scope

* For the future implementations, we could introduce some more features which can act as a major factor in approval or rejection of loans. 
* We could also increase the training data size. 
* We will extend this project to deploy it on heroku with an efficient UI/UX for a non technical person to implement these techniques in a more convienient manner.
