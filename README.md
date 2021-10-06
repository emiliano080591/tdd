# TDD Python
TDD example with Python (Flask and Pytest)

## First run
```shell
$ python blog/init_db.py
$ FLASK_APP=blog/app.py python -m flask run
```

### Run tests
```shell
$ python -m pytest tests
```

### Run coverage
```shell
$ python -m pytest tests --cov=blog
```

### To run only the e2e tests
```shell
$ python -m pytest tests -m 'e2e'
```

### To run all tests except e2e
```shell
$ python -m pytest tests -m 'not e2e'
```

### Run lint
```shell
$ python -m flake8 /blog
```

### Run code formatter
```shell
$ python -m isort .
```