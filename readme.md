# About
The Adara Data Onboarding challenge involves building a lightweight micro-service API for the Adara Traveler Intelligence platform. 
Fundamentally API clients will be getting data from the API in order to customize data in the browser. 
 
An API stub has been provided using Connexion a Design-First Swagger implementation built on top of Flask. 
Data tables have been provided in csv format. You are free to load the data into memory or implement a database.
However, you must include instructions on how to set up your development environment.

There are 4 issues available in the git repository. You must complete at least 2 tasks.

This test is meant to evaluate 4 skills:

1. Python Development
2. Git Workflow
3. Basic Testing 
4. Documentation

During the Code Pair session, you will be expected to run the server and connect your local environment to a public url 
using something like ngrok.

## Setup
1. Fork this repository.
2. Create a virtual environment using Python 3.7.0
3. Install the requirements
4. Execute the tests using

        python manage.py test
5. Run the server using 
        
        python manage.py run
6. Access the Swagger UI here:

        http://localhost:5000/api/v1.0/ui
        
## Process
Using the GitFlow model: Create features against the develop branch and create pull request for each new feature.

Each feature should: 
1. Include tests under /app/tests
2. Include descriptive docstrings with arguments and return variables (see Google's Sphinx Format)
3. Include API documentation in the Swagger yml 

