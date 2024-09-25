Titanic Survival Prediction Project

Overview

This project aims to predict the survival of passengers on the Titanic using machine learning techniques. The prediction is based on various features such as age, gender, class and fare paid.

Dataset

The dataset used in this project is titanic.csv, which contains the following columns:

- PassengerId: Unique identifier for each passenger
- Survived: Survival status (0 = No, 1 = Yes)
- Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name: Name of the passenger
- Sex: Gender of the passenger
- Age: Age of the passenger in years
- SibSp: Number of siblings or spouses aboard the Titanic
- Parch: Number of parents or children aboard the Titanic
- Ticket: Ticket number
- Fare: Fare paid for the ticket
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

Libraries Used

- Pandas: For data manipulation and analysis
- NumPy: For numerical computations
- Matplotlib: For basic data visualization
- Seaborn: For advanced data visualization
- Scikit-Learn: For building and evaluating the prediction model

Steps Involved

1. Load Data: Read the dataset into a data frame
2. Exploratory Data Analysis (EDA): Understand the data structure and visualize relationships using graphs and charts
3. Data Cleaning: Check for missing values and handle them appropriately
4. Feature Engineering: Create new features and convert categorical variables into numerical formats
5. Split Data: Divide the dataset into features and target variables and then into training and testing sets
6. Model Building: Use logistic regression or other classification algorithms to build the prediction model
7. Evaluation: Assess the model's performance using accuracy, confusion matrix and classification report

Results

The model provides insights into the factors influencing survival on the Titanic, allowing for predictions based on passenger characteristics.

How to Run

1. Clone the repository.
2. Ensure you have the required libraries installed (pip install pandas numpy matplotlib seaborn scikit-learn).
3. Run the Jupyter Notebook or Python script to see the results.
