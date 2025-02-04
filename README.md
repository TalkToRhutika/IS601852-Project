# My project install instructions

## install

1. clone
2. pip install -r requirements.txt

## Testing

1. pytest
2. pytest --pylint
3. pytest --pylint --cov

## Notes
1. python version 3.12.3 latest stable is installed already
2. vs code and python microsoft extension is installed already
3. go to the project directory from vscode terminal
4. create virtual environment for python in the vscode pip3 install virtualenv  
5. run command in the vs code terminal.   cd /projectfolder   python3 -m venv venv
6. activate the virtual environment.  source venv/bin/activate
7. install testing libraries pip3 install pytest pytest-pylint pytest-cov
8. freeze requirements pip3 freeze > requirements.txt
9. add code for calculator and test in the project
10. run tests to check the code. pytest --pylint --cov

