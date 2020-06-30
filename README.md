# Weight-Prediction
This model is intended to predict the weight of an individual based on variables that are thought to contribute to a persons weight such as hieght, arm circumference, waist circumference, etc. The model is trained and tested on the National Health and Nutrition Exam Survey (NHANES) for 2017-2018.

## Data Conversion from XPT
Data was pulled from the CDC's National Health and Nutrition Exam Survey for 2017-2018 in XPT format. The data came in two separate files that were combined in Python. Only variables that were intuitively beleived to have predictive power were chosen. After selecting these variables, the combined data was converted into a CSV format.

## Data Visualization
Before preprocessing and cleansing, visualization was done to ensure that variables chosen had some sort of relationship with the independent weight variable. 

## Data Cleansing and Preprocessing
After visualization was complete, cleansing and further preprocessing was initiated to handle missing values and select final variables. Categorical variables were converted into dummy variables and one variable from each category was removed as a reference variable.  

## Model Building
Building the model was fairly straight forward. The data was split into test and training datasets. A linear regression model was trained on the training dataset. After training, the model was applied to the test dataset where it proved to be an accurate model.

## Results
The model proved to be accurate in predicting a persons weight based on the variables that were inputted.



