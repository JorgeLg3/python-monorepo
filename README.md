# Initial setup
How to setup the local sandbox to work in project_A. Using the editable installs allow us to import a local package directly from source code.
* the following code it's for Windows machines. Other OS will have slightly different implementation
```shell
cd project_A
python -m venv .venv
.venv/Scripts/activate
pip install -r pip-requirements.txt
pip install -r dev-requirements.txt
pip install -r requirements.txt
```

# Running the project_A executable
If you can run the following command and print a 11 in the console, you have succesfully importaed a functionality from a local python package.s
```shell
python -m main
```