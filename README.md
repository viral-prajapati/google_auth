
# Google authentication website

This is Google authentication django web applcation using auth.


## Installation

- Install and create virtual environment with pip

```bash
  $ python -m venv env
  $ \env\Scripts\activate
```

- Install required modules with pip

```bash
  $ pip install -r requirements.txt
```

- create .env file in `google` folder and add below values in it.

```bash
  KEY=##############
  SECRET=#############
```
- Now, run the server using below command

```bash
  $ python manage.py runserver
```