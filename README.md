## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
  * [Python](#python)
  * [Docker](#docker)

## General info
This project is simple todo app for practise.

## Technologies
Project is created with:
* Python: 3.11
* Flask: 2.3.2
* Flask-SQLAlchemy: 3.0.5
* Chota CSS: 0.9.2

## Setup
To run this project:

### Python
```shell
$ cd ../flask-todo-app
$ pip install -r requiremets.txt
$ python app.py
```

### Docker
````shell
cd ../flask-todo-app
docker build -t flask-todo-app .
docker run -p 5000:5000 flask-todo-app
````