# fastapi-tutorial-sqlite
Tutorial for connection fastapi with sqlite database and create crud operation.

### How to run:
- open cmd in this project folder
- run virtualenv : fastapi-venv\scripts\activate
- change project directory : cd fastapi-tutorial-sqlite
- run command : uvicorn main:app --reload


### Other Commands

command to create virtual env 
```
python -m venv fastapi-venv
```
command to freeze requierements
```
pip freeze > requirements.txt
```
command to install reruirements (make sure your virtual env is activate)
```
pip install -r requirements.txt
```

check home page api on url : http://127.0.0.1:8000
check api doc on url : http://127.0.0.1:8000/docs
check api doc on url : http://127.0.0.1:8000/redoc