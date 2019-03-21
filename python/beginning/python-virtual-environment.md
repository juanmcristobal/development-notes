# Python Virtual Environment

## Install Python Virtualenv
To install Python’s virtual environment:
`sudo apt install virtualenv`
Create New Directory in Home
Navigate to your users home directory:

cd
Create a directory named python-environments:

mkdir python-environments
Navigate in the newly created directory:

cd python-environments
Create a Virtual Environment in Python 3Permalink
Create a virtual environment in Python 3 with the environment name of env:

virtualenv -p python3 env
Validate that environment is installed with python3:

ls env/lib
Activate EnvironmentPermalink
Activate the newly created virtual environment (the name of the working environment will appear in parentheses):

source env/bin/activate
(env) testuser@localhost:~/python-environments$
Now that the environment is active, you can install executables and packages only to this virtual environment.

Deactivate EnvironmentPermalink
To deactivate an active virtual environment:

deactivate
Congratulations! You have created an isolated, Python Virtualenv on your Linode.
