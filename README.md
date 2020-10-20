# My first project using CRUD with Flask
Simple API Rest created to learn how to use CRUD, and made with Flask.

&nbsp;


## Description
The idea of ​​the project is to display a json file in the browser with the developers from the list that is in app.py.
## Technologies
The project ran on a venv with python 3.9.0 and flask 1.1.2.

&nbsp;

## Setup
```
$ pip install -r requirements.txt
$ python3 app.py
```

## Routes

`GET - /devs`

>Displays the json file with a developer's id, name and programming language.


`GET - /devs/<string:lang>`
> Filters devs by programming language.

`GET - /devs/<int:id>`
> Filters devs by id

`PUT - /devs/<int:id>`
> Updates dev information.

`POST - /devs`
> Adds a new dev.

`DELETE - /devs/<int:id>`
> Deletes the dev.