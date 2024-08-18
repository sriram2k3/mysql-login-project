# MySQL-login_page-project

## Description:
This Python script creates a basic login application using Tkinter for the GUI and MySQL for user authentication.

## Dependencies:
* Python 3.x
* Tkinter
* mysql-connector-python

## Installation:
* Install the required dependencies using pip:
  * pip install tkinter mysql-connector-python


* Create a MySQL database named "work" with a table named "CREDENTIALS" having columns "USERNAME" and "PASSWORD".
Usage:

  * Replace the placeholder database credentials (host, user, password) with your actual database information.
  * Run the Python script.
  * Enter your username and password.
  * The script will attempt to authenticate the user against the database.
  * If successful, a "Successfully Logged in" message will be displayed.
  * If unsuccessful, an "Incorrect username or password" message will be displayed.

## Code Structure:
* Imports: Imports necessary libraries.
* submitact function: Handles user input and calls the login function.
* login function: Connects to the database, executes the login query, and displays appropriate messages based on the result.
* GUI: Creates the Tkinter GUI with entry fields for username and password, and a submit button.
