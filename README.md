Python Programming

Create a Simple Python Application for a fictional chocolate house that uses SQLite to manage,
->Seasonal flavour offerings
->Ingredient inventory
->Customer flavor suggestions and allergy concerns

# Chocolate House Web Application

This is a simple web application for a fictional chocolate house that allows users to manage seasonal flavor offerings, ingredient inventory, and customer flavor suggestions with allergy concerns. The application is built using Python's Flask framework and uses SQLite as the database.

## Features

Manage Seasonal Flavors: Add, view, and delete seasonal chocolate flavors.
Ingredient Inventory: Add, view, and delete ingredients used in chocolate production.
Customer Feedback: Submit feedback regarding flavors and report any allergy concerns.

## Technologies Used

Python: Programming language for the backend.
Flask: Web framework for building the web application.
SQLite: Lightweight database for storing data.
HTML/CSS: For front-end development.

##Prerequisites

Before running the application, ensure you have the following installed:
Python 3.x: Download from python.org.
Flask: This will be installed in the setup steps.

##Step-by-Step Instructions to Run the Application

1.Clone or Download the Project
If you have a repository set up, clone it using:
--> git clone https://github.com/yourusername/chocolate_house_app.git
--> cd chocolate_house_app

2.Create a Virtual Environment
-->python -m venv venv

3.Activate the Virtual Environment
-->venv\Scripts\activate

4.Install Flask
With your virtual environment activated, install Flask using pip:
-->pip install Flask

5.Set up the Database
Run the database setup script to create the SQLite database and tables:
-->python database_setup.py

6.Run the Flask Application
Now you can run your Flask application with:
-->python app.py

7.Access the Application in Your Browser
Open your web browser and go to:
-->http://127.0.0.1:5000/

##Application Features

Manage Seasonal Flavors: Add new flavors, view existing flavors, and delete flavors.
Ingredient Inventory: Add ingredients, view stock levels, and delete ingredients.
Customer Feedback: Submit feedback for flavors including allergy concerns.

##Example Usage
To add a new seasonal flavor, fill out the form on the homepage under "Add New Flavor."
To manage ingredients, use the section labeled "Add New Ingredient."
To submit feedback regarding flavors, click on "Submit Feedback" on the homepage.

##Troubleshooting
Ensure that your virtual environment is activated before running the application.
If you encounter issues with Flask not being found, double-check that it is installed in your active virtual environment.
Make sure that database_setup.py runs without errors to create necessary tables.

##Testing the Application

##Test Steps
To validate that the application is functioning correctly, follow these test steps:

1.Access Home Page
-->Open your web browser and navigate to http://127.0.0.1:5000/.
-->Verify that the homepage loads without errors.

2.Add a New Seasonal Flavor
-->Click on "Add New Flavor."
-->Fill in the form with valid data (e.g., Flavor Name: "Mint Chocolate", Season: "Winter", Details: "Refreshing mint chocolate flavor").
-->Submit the form.
-->Verify that you are redirected back to the homepage and that the new flavor appears in the list of available flavors.

3.Add a New Ingredient
-->Click on "Add New Ingredient."
-->Fill in the form with valid data (e.g., Ingredient Name: "Cocoa Powder", Stock Quantity: 100).
-->Submit the form.
-->Verify that you are redirected back to the homepage and that the new ingredient appears in the ingredient inventory list.

4.Submit Customer Feedback
-->Click on "Submit Feedback."
-->Fill in the form with valid data (e.g., Flavor Name: "Mint Chocolate", Allergy Info: "None", Feedback: "Loved it!").
-->Submit the form.
-->Verify that you are redirected back to the homepage.

5.Delete a Seasonal Flavor
-->From the homepage, locate an existing flavor in the list.
-->Click on "Delete" next to that flavor.
-->Verify that you are redirected back to the homepage and that the deleted flavor no longer appears in the list.

6.Delete an Ingredient
-->From the homepage, locate an existing ingredient in the inventory list.
-->Click on "Delete" next to that ingredient.
-->Verify that you are redirected back to the homepage and that the deleted ingredient no longer appears in the inventory list.

##Expected Results
The application should not throw any errors during navigation or form submissions.
All added flavors, ingredients, and feedback should be displayed correctly on their respective pages.
Deleted items should no longer appear in their respective lists.

##Acknowledgments
Thanks to Flask for providing a simple framework for web applications.
Thanks to SQLite for being a lightweight database solution.

