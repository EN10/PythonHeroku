# Simple Python Web App for Heroku

[Heroku Example](https://flaskapp01.herokuapp.com)

#### Install

    sudo pip install heroku gunicorn flask

**Setup Git**

    git init
    git add app.py Procfile requirements.txt 
    heroku git:remote -a flaskapp01
    git commit -am "init"
    git push heroku master
    
cs50 debug:

    	app.run(host='0.0.0.0', port=8080)

[Flask Example](http://flask.pocoo.org)
[Bash in Python](http://blog.nuventure.in/2014/09/04/executing-bash-commands-via-python)