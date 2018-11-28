# BLOGGER APP

# Author
By Fred Kheisa

## Link to Deployed Site on Heroku

## Description
This is a web application for people to post blogs and also other people can comment on the application and like and dislike


## Installation Requirements:gear:
- Make a directory on your pc to host the application.
- Initialize git on the folder using the following command;
    `$ git init`
- On your terminal,Navigate to created directory.
- Run the following commands to allow functionality of the app:-

`sudo apt-get update` 
`sudo apt-get install python3.6` for python installations
`python3.6 -m venv virtual` for the virtual environment
`source virtual/bin/activate` for activating the virtual environment
- Download the latest version of pip in the virtual environment: `$ curl https://bootstrap.pypa.io/get-pip.py | python`
`pip install -r requirements.txt` for installations of flask extensions

## Application Requirements
- alembic==0.9.9
- blinker==1.4
- click==6.7
- dominate==2.3.1
- Flask==1.0.2
- Flask-Bootstrap==3.3.7.1
- Flask-Login==0.4.1
- Flask-Mail==0.9.1
- Flask-Migrate==2.2.1
- Flask-Script==2.0.6
- Flask-SQLAlchemy==2.3.2
- Flask-Uploads==0.2.1
- Flask-WTF==0.14.2
- itsdangerous==0.24
- Jinja2==2.10
- Mako==1.0.7
- MarkupSafe==1.0
- psycopg2==2.7.5
- psycopg2-binary==2.7.5
- python-dateutil==2.7.3
- python-editor==1.0.3
- six==1.11.0
- SQLAlchemy==1.2.8
- visitor==0.1.3
- Werkzeug==0.14.1
- WTForms==2.2.1


## User Stories :family:
The application user can:
- See the blogs posted.
- Comment on blogs.
- View the most recent blogs
- Be alerted when a new post is made by subscribing.

The application admin is able to:
- Sign in to the app.
- Create a blog in the application.
- Emit comments that are considered insulting or degrading.
- Update or filter blogs created.

## Technologies Used :Computer :
- Python 3.6.6
- HTML5
- CSS3
- Bootstrap4
- Flask Framework
- Postgresql
- Visual Studio Code text editor

## Known Bugs
sending confirmation message to the sign up email is the only known bug

## Deployment Host
- Heroku

## Support and Contact Details
Be sure to contact us at fredkheisa@gmail.com

## License
*MIT License*
Copyright (2018) (FRED KHEISA)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
