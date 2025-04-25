# Task-management-system

This Task Manager REST API project was built using Flask and is designed to provide users with a way to:

Register and log in.
Add, view, and delete personal tasks.
Authenticate using a simple token-based logic (no external authentication).
Store all data in a local JSON file for persistence.


1. Project Setup:
Flask was used as the web framework for setting up the routes and handling API requests.
Data is stored in data.json, which is a file-based storage solution.

2. User Registration (/register):
Users provide a username and password.
The backend checks if the username already exists.
If not, a new user is created and assigned a token.

3. User Login (/login):
Users log in using their username and password.
If valid, a token is returned for future use in authenticated requests.

4. Token-Based Authentication:
All task-related
