## Python Flask Authentication

This repository contains the code used in the Python Flask Authentication [video](https://www.youtube.com/watch?v=71EU8gnZqZQ) uploaded on [my YouTube channel](https://www.youtube.com/watch?v=71EU8gnZqZQ).

If on python 3.10 plus the following commands may be needed to create/recreate the database file.
```
export FLASK_APP=app
flask shell  # this instead of python3 (python shell)
from app import db,app
db.drop_all()
db.create_all()
```

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required dependencies

##### Windows:
```zsh
pip install -r requirements.txt 
```

##### macOS/Linux:
```zsh
pip3 install -r requirements.txt
```

## Usage

##### Windows:
```zsh
python app.py
```
##### macOS/Linux:
```zsh
python3 app.py
```
