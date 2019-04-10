# ToDo project

## How to Install
#### Cloning the directory
* Run ``` git clone https://github.com/Rsingh2805/ToDo```
* Move into the directory ```cd ToDo(Or repository folder)```
#### Creating A Virtual Environment
* Run ```virtualenv venv``` to create a virtual environment by the name venv.
* To activate the environment ```source venv/bin/activate```
* To deactivate run ```deactivate```

####Installing prerequisites
* After activating the environment run ```pip install -r requirements.txt```

#### Running the project
* To make migrations for the Django Models (To be done after changing the models.py file)
```
python manage.py makemigrations
python manage.py migrate
```

* To run the project
```
python manage.py runserver
```