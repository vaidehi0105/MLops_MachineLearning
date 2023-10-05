# MLops_MachineLearning
Implementing Simplified MLops for a Machine Learning Project

## Step 1: Version Control

 1. Create a new public GitHub repository for your MLops assignment.
 2. Initialize the repository with a README file
 3. Write a simple Python script to train a machine learning model on a dataset of your choice. Here I have used dataset from sklearn datasets which is diabetes datasets. Columns in this dataset are Pregnancies, Glucose, Blood Pressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age and Diabetes(0 or 1) and I have used XG Boost classifier to predict the label.
 4. Commit your code to the repository and push it to GitHub.

## Step 2: 


<!-- 3. Heroku Account (create account , cloud platform in order to deploy the application) -->

In order to dockerize my application I followed these steps:
step 1. After using standard scaler in my ML code i created a pkl file so that I can scale the values after every new input. Secondly I have also created model.pkl file which will be used in prediction.

step 2: open VS Code and create requirements.txt file in this file we need to write all the necessary libraries and tools. Once all the requirements are mentioned we need to open commond prompt and type the code given below.

```pip install -r requirements.txt```



step 3: Once all the installation is done, create a file called app.py . code is provided in repository

step 4: To check if the code is properly working create another template folder and in that folder create home.html file 

Now run the code by using following command in command propmt 

```python app.py```

step 4: Create new POST request in POSTMAN where body is raw and is in json format.In my case the input is as follows :

```{"data":{"Pregnancies":1,"Glucose":148,"BloodPressure":72,"SkinThickness":35,"Insulin":0,"BMI":33,"DiabetesPedigreeFunction":1,"Age":50}}```



