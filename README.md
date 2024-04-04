# anly5300-project-group-7

## Authors

Andrea Dukic
ad1589@georgetown.edu

Austin Barish
abb110@georgetown.edu

Raunak Advani
ra1113@georgetown.edu

Shingai Nindi
smn78@georgetown.edu

## Project Description

In this project we will deploy a variety of statistical modeling methods to understand the factors in student academic success measured as both a categorical variables (graduate/dropout) and a continuous variable (Grade). To do this we will use the data from UC Irvine Machine Learning Repository titled [Predict Students' Dropout and Academic Success](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success). The data contains 4424 instances and 36 features. It can be found in the `data` folder of this repository as [academic-success.csv](data/academic-success.csv) for R or imported into python [using](https://github.com/uci-ml-repo/ucimlrepo):

```python
from ucimlrepo import fetch_ucirepo 
  
# fetch dataset 
predict_students_dropout_and_academic_success = fetch_ucirepo(id=697) 
  
# data (as pandas dataframes) 
X = predict_students_dropout_and_academic_success.data.features 
y = predict_students_dropout_and_academic_success.data.targets 
  
# metadata 
print(predict_students_dropout_and_academic_success.metadata) 
  
# variable information 
print(predict_students_dropout_and_academic_success.variables) 
```

## Data Citation

Realinho,Valentim, Vieira Martins,Mónica, Machado,Jorge, and Baptista,Luís. (2021). Predict Students' Dropout and Academic Success. UCI Machine Learning Repository. https://doi.org/10.24432/C5MC89.
