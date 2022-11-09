# made from this tutorial

https://www.digitalocean.com/community/tutorials/how-to-add-authentication-to-your-app-with-flask-login

# setup

use virtualenv and virtualenvwrapper to create a new virtualenv
`mkvirtualenv flask`

switch to the virtualenv
`workon flask`

install packages
`pip install`

make run script executable
`chmod +x run.sh`

run local server on port 3333 with debug mode on
`./run.sh`

the sqlite database will be created automatically at this point in a folder called instance if it does not already exist.

## ideas
* consider using Flask-User and/or Flask-Security libraries