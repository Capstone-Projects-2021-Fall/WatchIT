### Setting up Virtual Environment

Skip the mkdir steps
https://flask.palletsprojects.com/en/2.0.x/installation/

Go to ../WatchIT/Back
To create venv:
```
py -3 -m venv venv
```

To activate venv:
```
venv\Scripts\activate
```

## To start server
1. Go to ../WatchIT/Back in your terminal
2. PICK ONE!!!
Bash
```
$ export FLASK_APP=flaskr
$ export FLASK_ENV=development
$ flask run
```
CMD
```
> set FLASK_APP=flaskr
> set FLASK_ENV=development
> flask run
```
Powershell
```
> $env:FLASK_APP = "flaskr"
> $env:FLASK_ENV = "development"
> flask run
```
