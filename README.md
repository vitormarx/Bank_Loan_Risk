# Bank_Loan_Risk
Data analysis and Machine Learning project to predict which pearson should pay a bank loan. This project can be used to help banks to reduce money loss by loan 

### Technologies

- **IDE**:Google Colaboratory / Jupyter Notebooks
- **Programing Lenguage**: Python 3.8.10

### About the Dataset
This dataset includes personal and bank information about people whos needed a loan from an especific bank and whether they payed or not the credit conceded by the bank

- **features:**
    -clientid	
    -income	
    -age	
    -loan	
    -default

Link to <a href=''>credit</a> dataset

### Running the Project
Firstly, you need to clone this repository as showed bellow:
```console
git clone --branch main https://github.com/vitormarx/Bank_Loan_Risk.git
```
then,  run it on Google Colaboratory or Jupyter Nootebook. Same as Windows as Linux OS

Once the download has completed, you can open the Bank-Loan-Risk.ipynb file and check the project steps.

### Model Evaluation
The model was trained on many machine learning algorithms (Naive Bayes, Random Forest, KNN, SVM and Neural Network). The one with better performance was the neural network, as showed bellow:

- **Accuracy**: 99.8%

![screenshot](/images/confusion_RNN_matrix.jpeg)
