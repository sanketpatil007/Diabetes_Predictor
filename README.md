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
