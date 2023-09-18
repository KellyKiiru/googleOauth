# googleOauth
Python Django project implementing google Oauth user registration

Git clone this repo with 
```
git clone https://github.com/KellyKiiru/googleOauth.git
```

cd googleOauth

create a virtual environment
```
python -m venv virtual
```

Install all project packages

```
pip install -r requirements.txt
```
Create a .env and .gitignore file in the project's root directory
Store your [Google](https://console.cloud.google.com/) secrets [CLIENT ID, CLIENT SECRET] in this file using the foo=bar format 
```
CLIENT_ID='your-google-unique-id'
CLIENT_SECRET='your-google-unique-secret'
```

The project uses PostgreSQL

Configurations in .env file
```
NAME='googleauth' //db name
USER='postgres'
PASSWORD='yourpassword'
PORT='5432'
```

Run the server

```
python manage.py runserver
```

