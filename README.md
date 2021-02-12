# Flask Blog App

## Setup

### Virtual Environment
- Install a virtualenv if not already installed
```shell
python3 -m pip install --user virtualenv
```
- Create a virtual environment
```shell
virtualenv env
```
- Activate environment
```shell
source env/bin/activate
```

### Install requirements
```shell
pip install -r r.txt
```

### Flask Environment variables
```shell
export FLASK_APP=app
export FLASK_ENV=development
```
### DATABASE
- Run the following command to initialize the database
```shell
python init_db.py
```
## Run the server
- The following command will run development server on `http://127.0.0.1:5000`
```shell
flask run
```

## Usage  

* You can use the following urls to view, create, edit or delete apps
    * http://127.0.0.1:5000
    * http://127.0.0.1:5000/<id>
    * http://127.0.0.1:5000/<id>/edit
    * http://127.0.0.1:5000/create
    