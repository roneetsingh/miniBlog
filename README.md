# miniBlog
# GameStore

## Table of contents

- [Introduction](#introduction)
- [Demo](#demo)
- [Technology](#technology)
- [Features](#features)
- [Database Models](#database)
- [Run](#run)
- [License](#license)

## Introduction

• This is a simple Blogging application, developed using the Flask Framework.

• This application has a really Minimal UI, and comes packed with all the basic functionalities of a blogging website.

• Tech Used: Python-Flask, HTML, CSS, Bootstrap.

• Utilities Used: Bcrypt, Pillow, Python-dotenv, SQLAlchemy, Werkzeug, WTForms, Waitress.

## Demo



The application is deployed on Heroku and can be accessed through the following link:

[miniBlog on Heroku](https://miniblogflasker.herokuapp.com/)

The website is a blogging application and you can create posts on the website and publish them.

## Technology

The application is built with:

- bcrypt==3.2.0
- blinker==1.4
- certifi==2021.5.30
- cffi==1.14.6
- charset-normalizer==2.0.2
- click==8.0.1
- colorama==0.4.4
- dnspython==2.1.0
- email-validator==1.1.3
- Flask==2.0.1
- Flask-Bcrypt==0.7.1
- Flask-Login==0.5.0
- Flask-Mail==0.9.1
- flask-ngrok==0.0.25
- Flask-SQLAlchemy==2.5.1
- Flask-WTF==0.15.1
- greenlet==1.1.0
- gunicorn==20.1.0
- idna==3.2
- itsdangerous==2.0.1
- Jinja2==3.0.1
- MarkupSafe==2.0.1
- ngrok==0.0.1
- Pillow==8.3.1
- pycparser==2.20
- python-dotenv==0.18.0
- requests==2.26.0
- six==1.16.0
- SQLAlchemy==1.4.21
- urllib3==1.26.6
- waitress==2.0.0
- Werkzeug==2.0.1
- WTForms==2.1

## Features

The application is a Blogging website.

Users can do the following:

- Create an account, login or logout.
- Browse available posts added by other bloggers.
- Add posts to the website.
- Delete or edit posts on their account.
- View their posts.
- The profile contains all the informations about the user.
- User can edit their account info change email, username or profile picture.

## Database

- SQLite database is used to store Users & Posts details.

 ### User Schema:

- id(Primary Key)
- username(Number)
- email(String)
- image_file(Image)
- password(String)
- posts(Relationship to post)

### Posts Schema:

- id(Primary Key)
- title(String)
- date_posted(DateTime)
- content(Text)
- user_id(Foreign Key)

## Run

To run this application
- You need to install [Technology](#technology) items using pip install -r requirements.txt
- Set your SECRET_KEY
- Set your EMAIL_USER
- Set your EMAIL_PASS
- Set your Database
- Run <b>python python run.py</b> on your terminal 

## License

[![License](https://img.shields.io/:License-MIT-blue.svg?style=flat-square)](http://badges.mit-license.org)

- MIT License
- Copyright 2021 © [Roneet Kumar Singh](https://github.com/roneetsingh)
