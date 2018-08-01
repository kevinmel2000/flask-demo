# flask-demo
Flask app usage demo
Small app to understanding a fundamentals of web development in Python using Flask

## Requirements
Python >= 3.5
Pipenv

## Setup
1. Clone App
```bash
git clone https://github.com/imamdigmi/flask-demo.git
```
2. Install dependencies
```bash
pipenv install
```
3. Activate virtual envirounment
```bash
pipenv shell
```

## Run
```bash
export FLASK_APP=microblog.py
```

```bash
flask run
```

The app should running on [http://127.0.0.1:5000](http://127.0.0.1:5000/)

## Aditional
To test send email for debugging server
```bash
python -m smtpd -n -c DebuggingServer localhost:8025
```
This is a fake email server that accepts emails, but instead of sending them, it prints them to the console.