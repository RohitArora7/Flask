# Flask

app.py

```bash
from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
	return "HELLO"


if __name__ == "__main__":
    app.run(debug=True)	
```


Start
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


Browser
```bash
http://localhost:5000/
```
