## Flask Demo

Simple Flask app to test live reload

## Intro

This project will test various configurations for running a Flask app in debug mode. Check other branches for other approaches.

### Installing the App

To get the server set up on your local system, use the following commands after cloning the repo

```
# create a virtual environment
python3 -m venv venv

# activate the virtual environment
source venv/bin/activate

# install the dependencies
pip install -r requirements.txt
```

### Running the App

To run the app in debug mode, use the following command

```
flask --debug run
```

This will run the app in a way which restarts the server whenever the file is edited.
