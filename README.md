# Flask

Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries

**App.py**

```bash
from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
	return "HELLO"


if __name__ == "__main__":
    app.run(debug=True)	
```


**Start**
```bash

pip install --upgrade pip virtualenv virtualenvwrapper
virtualenv env
source env/bin/activate

pip install Flask==1.1.2
pip install Flask-SQLAlchemy==2.4.4
or
pip3 install flask flask-sqlalchemy

python3 app.py
```


**Browser**
```bash
http://localhost:5000/
```


**log**
```bash
 * Serving Flask app 'app' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Running on http://127.0.0.1:5000 (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 931-960-244
127.0.0.1 - - [20/May/2022 10:41:41] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [20/May/2022 10:41:41] "GET /favicon.ico HTTP/1.1" 404 -
127.0.0.1 - - [20/May/2022 10:44:31] "GET / HTTP/1.1" 200 -
```
