# A3G7-FINAL

Through this project, we have deployed a Flask web application with a MySQL data base using Docker and Docker Compose. It shows the application networking, secure handling of environament variables, and a stuctured collaborative workflow. 

Project Overview
This application includes:
1.⁠ ⁠Flask Web Application: Shows a message retrieved from an environment variable and connects to a MySQL database.
2.⁠ ⁠MySQL Database: Manages data storage and retrieves the application.

Process of the Project

Step 1: Creating the Repository
The project started with creating a Git repository to store all the project files and facilitate collaboration.

Step 2: Creating Feature Branches
We created two feature branches to separate concerns:
•⁠  ⁠feature/app: Dedicated to the development of the Flask application.
•⁠  ⁠feature/docker: Focused on the Docker setup, including the MySQL configuration.

Step 3: Adding Files to Each Branch
•⁠  ⁠In feature/app, we added:
  - Dockerfile for the Flask application.
  - app.py containing the Flask application code.
  - requirements.txt for dependencies.
•⁠  ⁠In feature/docker, we added:
  - image.txt specifying the MySQL image to use in the database container.

Step 4: Merging into Main
Once both branches were complete, they were merged into the main branch to consolidate all the components.

Step 5: Adding Remaining Files
From the main branch, we continued to enhance the project by adding:
•⁠  ⁠.gitignore: To exclude sensitive files like .env.
•⁠  ⁠.env: Environment variables to store credentials and configurations.
•⁠  ⁠Documentation:
  - SECURITY_EXPLANATION.txt: Importance of protecting .env files and avoiding credential exposure.
  - NETWORK_EXPLANATION.txt: Custom networking, DNS resolution, and subnet considerations.
  - TROUBLESHOOTING.md: Documenting issues faced, their causes, and solutions.

Contributors

Albert Blade:
Created the repository and feature/app branch.
Added the Flask application files and updated the README.md.
Carlos Arcusa:
Created the feature/docker branch and added the MySQL image configuration.
Gael Mensa:
Added the .env file and included it in .gitignore.
Nick Bird:
Authored TROUBLESHOOTING.md and GROUP_REPORT.md.
Lucas Cayola:
Merged feature/app and feature/docker into main.
Added docker-compose.yml for orchestrating services.
Victor Perez:
Wrote SECURITY_EXPLANATION.txt and NETWORK_EXPLANATION.txt.
