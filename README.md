Contributing to the Volatility Call Option Project


Welcome to the Volatility Call Option project! This guide will help you get started with the setup and contribute to the development.

Prerequisites
Before contributing, make sure you have the following:

Git: Ensure Git is installed on your machine.
Python 3.10+: This project is compatible with Python 3.10 or higher.
Virtual Environment: It is highly recommended to use a virtual environment to manage dependencies.
Steps to Set Up the Project Locally

1. Clone the Repository
To get started, clone the repository to your local machine:
`git clone https://github.com/apostleoffinance/volatility_call_option.git`


2. Set Up a Virtual Environment
Create and activate a virtual environment to manage dependencies:
`# Create a virtual environment (named 'env')`
`python3 -m venv env`

`# Activate the environment`
`# On macOS/Linux`
`source env/bin/activate`

`# On Windows`
`.\env\Scripts\activate`


3. Install Dependencies
Install the required libraries from the requirements.txt file:
`pip install -r requirements.txt`


4. Work on Your Feature/Task
Create a new branch for the feature or fix you're working on:
`git checkout -b feature/your-feature-name`
Make your changes in the code (in /src) or documentation (README.md).

5. Commit Your Changes
Once you've made your changes, stage and commit them:
`git add .`
`git commit -m "Describe the changes you made"`

6. Push Your Changes
Push your branch to the remote repository:
`git push -u origin feature/your-feature-name`

7. Create a Pull Request
Go to the repository on GitHub and create a Pull Request (PR) to merge your changes into the `main` branch.

8. Keep Your Fork Updated
If you have forked the repository, make sure to keep it up-to-date with the original repository:

# Fetch latest changes from the original repository
`git fetch upstream`

# Merge changes into your local branch
`git checkout main`
`git merge upstream/main`


9. Testing
Write and run unit tests for new features and bug fixes. Test cases are located in the /tests directory.

To run tests:
`pytest tests/`

Let’s collaborate to build an amazing project!










