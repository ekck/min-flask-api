# REST API With Flask & SQL Alchemy
API using:
 Python Flask,
  SQL Alchemy,
    Marshmallow

Using Pipenv():
## Activate venv
$ pipenv shell

## Install dependencies
$ pipenv install

## Create DB
```
$ python
>>>from app import db
>>>db.create_all()
>>>exit()
```

## Run Server (http://localhst:5000)
python app.py


## Endpoints
|API|ENDPOINT|
|------|------|
|GET |/product|
|GET |/product/:id|
|POST |/product|
|PUT |/product/:id|
|DELETE|/product/:id|