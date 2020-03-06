(1) First, you'll want to create a .env file in the root folder.

Copy and paste the variables directly below into the .env file and complete using your proper information. 

URL='https://lambda-treasure-hunt.herokuapp.com/'
API_KEY='API_KEY_HERE'
NAME='[YOUR_NAME_HERE]'


(2) Next, run the following commands...

1. pipenv install

2. pipenv shell

(3) Check that requests and dotenv packages are installed in the Pipfile by running the command below.

- pipenv run pip freeze

--- If not, manually install one or both using the shell using the commands below.

- pipenv install requests

- pipenv install python-dotenv

(4) Now that the shell is running, run the start.py file to begin!