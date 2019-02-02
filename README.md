# Home task 11 (Flask Blog App)

## 1: Initial Setup

#### Clone project in a new directory:
```bash
cd path/to/a/new/directory
git clone https://github.com/MaksNech/pylab2018_ht_11.git
```

## 2: Getting Started

#### Start backend:
Inside project create virtual environment:
```bash
virtualenv -p python3 env
```
Then start virtual environment:
```bash
source env/bin/activate
```
Install packages using pip according to the requirements.txt file:
```bash
pip install -r requirements.txt
```
Inside project directory run app with terminal commands:
```bash
export FLASK_APP=flask_blog
export FLASK_ENV=development
flask run
```

## 3: Running the Tests
Inside project directory run tests with terminal commands:
```bash
coverage run -m pytest
coverage report
coverage html
```
