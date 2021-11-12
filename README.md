# Driving-Pattern-Classification

roject: Driving Pattern Classification with vehicle driving data
  - Depending on the Driving Pattern, we could control the vehicle efficiently and adapt the classification result in various ways.

Dataset : https://www.kaggle.com/veeralakrishna/aggressive-driving-data
  - Target : Driving Pattern(Class = [1:"Aggressive", 2:="Normal", 3:"Vague"])
  - Index 162,632
  - Data columns 21

Data Analysis :
  - fillna
  - one-hot encoding
  - Data Normalization(MinMax Scaler)

Model : Multi-Classification(XGBoost)
