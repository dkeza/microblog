* Link to tutorial
https://blog.miguelgrinberg

* Create python venv enviroment
sudo apt-get install python3-venv
python3 -m venv venv
pip install --upgrade pip

* Install Flask
pip install wheel
pip install flask

* Instal Flask components
pip install flask-wtf
pip install flask-sqlalchemy
pip install flask-migrate

git config credential.helper store

* To do before start coding
source venv/bin/activate
pip install flask
export FLASK_APP=microblog.py
flask run

* Flask interactive shell, defined in microblog.py
flask shell

* Flask database migration
flask db init
flask db migrate -m "users table"
flask db upgrade
