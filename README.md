 pythonwebapp
flask project

$ wget https://www.python.org/ftp/python/3.6.3/Python-3.6.3.tar.xz
 $tar xJf Python-3.6.3.tar.xz
 $cd Python-3.6.3
 $./configure
 $make
 $make install

$python3 -m venv myproject

$source myproject/bin/activate

pip install Flask

pip freeze > requirements.txt

vi app.py

Error:" * Serving Flask app "app" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
Traceback (most recent call last):"

(myproject) 15:07 ~/flaskexample $ export FLASK_APP=app
(myproject) 15:09 ~/flaskexample $ export FLASK_ENV=development
-------------------------directories---------------
Source code:/home/kutevaibhav01/flaskexample

Working directory:/home/kutevaibhav01/

WSGI configuration file:/var/www/kutevaibhav01_pythonanywhere_com_wsgi.py
