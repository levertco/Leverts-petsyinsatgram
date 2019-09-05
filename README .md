# Leverts petsyinstagram

###  Author
Levert Ouma

### Description
This is a personal clone of the popular photo-sharing site Instagram

### User Stories
1. Sign in to the application to start using.
2. Upload my pictures to the application.
3. See my profile with all my pictures.
4. Follow other users and see their pictures on my timeline.
5. Like a picture and leave a comment on it.

### How to use
Upon opening the website you will be prompted to sign up or sign in(if you are an existing user).You will then be able to see posts that other users have posted and also add your own posts.
A user will also have a personalized profile where they can edit their profile info and image.
You can also follow other users and view images posted by the users.

### Tech used :computer: 
1. Python
2. Django
3. Postgres
4. Heroku for deployment

## Set up and Installation

### Prerequisites
You will require:
#git
$ install git-all

#python3.6
$ install python3.6.

#django
$ pip install django==1.11

#postgres
$ install postgresql postgresql-contrib libpq-dev
```
### Requirements
1. config==0.4.0
1. dj-database-url==0.5.0
1. Django==1.11
1. django-bootstrap3==11.0.0
1. django-bootstrap4==0.0.7
1. django-heroku==0.3.1
1. gunicorn==19.9.0
1. Jinja2==2.10
1. MarkupSafe==1.1.0
1. Pillow==5.3.0
1. psycopg2==2.7.6.1
1. python-decouple==3.1
1. pytz==2018.7

### .Env file
1. SECRET_KEY='<SECRET_KEY>'
1. DEBUG=True #set to false in production
1. DB_NAME='tribune'
1. DB_USER='user'
1. DB_PASSWORD='password'
1. DB_HOST='127.0.0.1'
1. MODE='dev' #set to 'prod' in production
1. ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
1. DISABLE_COLLECTSTATIC=1

### Installation
1. To access this application on your command line, you need to clone it 
`git clone https://github.com/levertco/Leverts-petsyinsatgram.git`
1. Create a requirements.txt in the root folder and copy the requirements above.
1. Install the required technologies with
`pip install -r requirements.txt`
1. Create a .env file and copy the .env code above
1. You can then run the server with:
`python3.6 manage.py runserver`
1. You can make changes to the db with
`python3.6 manage.py makemigrations photos`
`python3.6 manage.py migrate`
4. You can run tests:
`python3.6 manage.py test photos`


### Known Bugs :x:
Currently, there are no known bugs

### Live link
You can view the live site [here]()
### Licence


Copyright (c)
