# Django Hello World App

This is a simple Django application that returns a JSON response with a "Hello World!" message.

## Setup Instructions

Clone the repository and navigate into it:

```bash
 git clone https://github.com/Prithuk/SoftwareArchitectAssignment-Django.git

cd django 
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
pip install django
python3 manage.py runserver # on mac/linux
python manage.py runserver # on windows
```


## Accessing the App

Open your browser and go to http://127.0.0.1:8000/
. You should see the following JSON response:

```

{"Message": "Hello World!"}


```

