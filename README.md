# Diabetes-Predictor
a ML model for predicting diabetes built using django

# Clone the repository to your local machine.
Install the required dependencies using pip:
pip install -r requirements.txt

# Run migrations to set up the database:
python manage.py migrate

# Start the development server:
python manage.py runserver
Navigate to http://localhost:8000 in your web browser to access the web application.

# Usage
1. Enter the required information such as age, BMI, blood pressure, etc. in the input fields on the home page.

2. Click on the "Predict" button to get the prediction.

3. The prediction will be displayed on the next page along with a message indicating whether the individual is likely to have diabetes or not.

# Model
The prediction model used in this web application is based on a logistic regression algorithm and was trained using the Pima Indians Diabetes Dataset.

# Problem Statement
Diagnosis of diabetes is considered a challenging problem for quantitative research.  A single parameter is not very effective to accurately diagnose diabetes and may be misleading in the decision making process. There is a need to combine different parameters to effectively predict diabetes at an early stage. 

# Solution
Integrating Data mining with machine learning model to create a web app in order to predict diabetes. Using previous data set about diabetes that would be fed to the model , enabling the model to predict the outcome based on independent factors such as blood pressure , insulin ,etc. Thus considering more than one factors for predicting diabetes would be giving more accurate results.

