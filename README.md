Titanic Survival Prediction Approach
Data Cleaning: Handled missing Age values with the median and dropped the Cabin column due to high missingness.
Feature Engineering: Derived FamilySize, IsAlone, and extracted Title from names to capture social status, which is a strong predictor of survival
Feature Selection: Used a Random Forest Classifier to rank features. Key features identified include Sex, Title, Fare, and Age.
Instructions: To run the analysis, install dependencies via pip install -r requirements.txt and run the scripts in the /scripts directory.
