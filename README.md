# Weight-Prediction
This is a prediction model intended to predict the weight of an individual based on data from the CDC. Variables contained in this model include: height, upper arm size, upper leg size, waist size, and BMI (to name just a few).

## Data Conversion from XPT
Data was pulled from the CDC's National Health and Nutrition Exam Survey for 2017-2018 in XPT format. The data came in two separate files that were combined in Python. Only variables that were intuitively beleived to have predictive power were chosen. After selecting these variables, the combined data was converted into a CSV format.

## Data Visualization
Before preprocessing and cleansing, visualization was done to ensure that variables chosen had some sort of relationship with the independent weight variable. 

## Data Cleansing and Preprocessing
After visualization was complete, cleansing and further preprocessing was initiated to handle missing values and select final variables. Categorical variables were placed in 0 and 1 format with 1 indicating that row belonged to that category. 

## Model Building
Building the model was fairly straight forward. The data was split into test and training datasets. A linear regression model was trained on the training dataset. After training, the model was applied to the test dataset where it proved to be an accurate model.

## Results
The model proved to be accurate in predicting a persons weight based on the variables that were inputted.



