# SWE573_Term_Project
This Repository contains the Term Project of SWE573 class in Bogazici Univesity.
## Authors:  **Dağlar Berk Erdem**
## Application
The application can be accessed through http://52.211.173.214:8000
Please be careful about links :)
## Introduction
LinkMe is a web based note-taking and posting application. Users can share, categorize contents from social media or blogs and interact with other users
through contents. Moreover, users can browse through spaces or tags to discover contents in a specific area.
## Installation
Clone this git repository by using the command:
```
git clone https://github.com/dberkerdem/SWE573_Term_Project.git
```
## Setup
Important Notes: 
- Suggested version of Python is Python 3.8.
- Run the following commands in your GIT Bash terminal.

### Creating Virtual Environment
Open your GIT Bash terminal.\
Go to root directory and install virtualenv package to your global environment with following commands:
```
cd
pip instal virtualenv
```
Create a virtual environment with following command:
```
virtualenv --python="</path/to/python.exe>" "</path/to/new/virtualenv/>"
```
Activate your virtual environment with following command:
```
source "</path/to/new/virtualenv>/scripts/activate"
```
Install site packages from requirements.txt with the following command:
```
pip install -r requirements.txt
```
### Local Run
Open the root directory of the project and execute the following command with terminal in order to run local server:
```
python manage.py runserver
```
To reach the web application go to **http://127.0.0.1:8000**.
