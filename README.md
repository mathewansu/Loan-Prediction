# Loan-Prediction

This project aim at predicting the status of Loan on basis of Gender,	Married,	Dependents,	Education	,Self_Employed,	ApplicantIncome,	CoapplicantIncome,	LoanAmount	Loan_Amount_Term,	Credit_Histor,y	Property_Area	Loan_Status of the customer applied for loan.

## Confusion Matrix
![alt text](https://github.com/mathewansu/Loan-Prediction/blob/main/Confusion%20Matrix.PNG)
### Business Insights
- Logistic regression: 81% accuracy
- False positives were very high when threshold is 0.5
- We can play with the threshold setting for giving priority to either precision or recall. If we grand loan to a person who can't pay back, it will affect the bank badly. Therefore we should reduce the false positive rate. Thatis we should increase precision. 
- Therefore, i have increased the precisio by reducing the threshold to 0.4
#### Feature Importance
- ApplicantIncome,CoapplicantIncome, Loan amount and Loan amount term has vvery less impact on the mpdel prediction
- Credit History played an important role in orediction
- Property_Area_Semiurban,Education_Not Graduate, Married and dependents alls played an important role in prediction	
