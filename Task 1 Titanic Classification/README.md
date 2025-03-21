## Titanic Classification Project
This project involves predicting the survival of passengers aboard the Titanic using a machine learning model. The task is to determine whether a passenger would survive the sinking based on various features such as socio-economic status, age, gender, and more.

## Dataset
The dataset used for this project is sourced from Kaggle. You can access it here:
(https://www.kaggle.com/datasets/benjamin1717/taitanic/data)

**The dataset includes the following files:**

•	**train.csv:** Training data to build and validate the model.

•	**test.csv:** Test data for making predictions.

## Features in the Dataset

•	**Survived:** Target variable (0 = Not survived, 1 = Survived)

•	**Pclass:** Passenger class (1 = First, 2 = Second, 3 = Third)

•	**Sex:** Gender (male, female)

•	**Age:** Age of the passenger

•	**SibSp:** Number of siblings/spouses aboard

•	**Parch:** Number of parents/children aboard

•	**Ticket:** Ticket number

•	**Fare:** Passenger fare

•	**Cabin:** Cabin number (if available)

•	**Embarked:** Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Features
1.	**Exploratory Data Analysis (EDA):**
   
o	Visualize relationships between features and survival using matplotlib and seaborn.

o	Analyze categorical features like Sex, Pclass, and Embarked.

o	Explore numerical features such as Age, Fare, and FamilySize.

2.	**Data Preprocessing:**
   
o	Handle missing values for Age, Embarked, and Fare.

o	Encode categorical variables like Sex and Embarked.

o	Feature engineering, including adding FamilySize and extracting titles from passenger names.

3.	**Model Development:**
   
o	Built and evaluated two machine learning models:
	Logistic Regression
	Random Forest Classifier

o	Evaluated models using accuracy, confusion matrix, and classification report.
4.	**Prediction:**

o	Generated predictions for the test dataset and saved them in a CSV file.

## Project Files

•	train.csv: Training dataset.

•	test.csv: Testing dataset for predictions.

•	titanic_classification.ipynb: Jupyter Notebook containing the code for EDA, preprocessing, model training, and evaluation.

•	titanic_predictions.csv: Output predictions for the test dataset.

•	README.md: Project documentation.

## Results

•	Achieved an accuracy of ~83% using the Random Forest Classifier.

•	Explored relationships such as:

  o	Gender: Females had a higher survival rate.
  
  o	Pclass: Passengers in 1st class had the highest survival rate.

## Contributing
•	Contributions are welcome! Fork the repository, create a branch for your feature or bug fix, and submit a pull request.

## Contact
•	For inquiries or collaboration opportunities, please reach out to me:

•	**Name**: Malak Ismail  

•	**Email**: malakismail706@gmail.com 

•	**LinkedIn**: https://www.linkedin.com/in/malakismail0/
