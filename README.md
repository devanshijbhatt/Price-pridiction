# Price-pridiction
Using linear regression techniques, the project's goal is to forecast property values based on square footage and additional attributes. The model is constructed using a training and testing dataset. To increase the accuracy of the model, several steps of data preprocessing are performed. After then, the forecasts are stored in a csv file.
## Dataset

- **Training Data:** `train_data.csv`
- **Testing Data:** `test_data.csv`

### Columns in Dataset

- `ID`: Identifier for each house
- `crim`: Per capita crime rate by town
- `zn`: Proportion of residential land zoned for lots over 25,000 sq. ft.
- `indus`: Proportion of non-retail business acres per town
- `chas`: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- `nox`: Nitric oxides concentration (parts per 10 million)
- `rm`: Average number of rooms per dwelling
- `age`: Proportion of owner-occupied units built prior to 1940
- `dis`: Weighted distances to five Boston employment centres
- `rad`: Index of accessibility to radial highways
- `tax`: Full-value property tax rate per $10,000
- `ptratio`: Pupil-teacher ratio by town
- `black`: 1000(Bk - 0.63)^2 where Bk is the proportion of black residents by town
- `lstat`: Percentage of lower status of the population
- `medv`: Median value of owner-occupied homes in $1000s (only in training data)

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- scipy
