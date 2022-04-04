# Bank_Loan_Risk
Data analysis and Machine Learning project to predict which pearson should pay a bank loan. This project can be used to help banks to reduce money loss by loan 

### Technologies

- Google Colaboratory
- Python 3.8.10
- Scikit Learning
- Numpy
- Pandas
- Matplotlib / seaborn

### About the Dataset
This dataset includes personal and bank information about people whos needed a loan from an especific bank and whether they payed or not the credit conceded by the bank.


Link to original <a href=''>dataset</a> 

### Running the Project
Firstly, you need to clone this repository as showed bellow:
```console
git clone --branch main https://github.com/vitormarx/Bank_Loan_Risk.git
```
then,  run it on Google Colaboratory or Jupyter Nootebook. Same to Windows and Linux OS

Once the download has completed, you can open the Bank-Loan-Risk.ipynb file and check the project steps.

### Model Evaluation
The model was trained on many machine learning algorithms (Naive Bayes, Random Forest, KNN, SVM and Neural Network). The one with better performance was the neural network, as showed bellow:

- **Accuracy**: 99.8%

![screenshot](/images/confusion_RNN_matrix.jpeg)


-*1* --> don't pay the loan

-*0* --> pay the loan
