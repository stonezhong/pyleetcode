# pyleetcode

# Test it locally
## Step 1: make sure you have python 3.x installed
Check the instruction [here](https://realpython.com/installing-python/) to install python3.

## Step 2: Create a virtual environment
```
mkdir ~/.venvs/pyleetcode
virtualenv -p python3 ~/.venvs/pyleetcode
source ~/.venvs/pyleetcode/bin/activate
pip install pip --upgrade
```
## Step 3: check out pyleetcode project source code
```
git pull git@github.com:stonezhong/pyleetcode.git
```

## Step 4: run the web site
first run
```
cd pyleetcode
python manage.pmigrate
python manage.py runserver 0.0.0.0:8080
```

In the future, just run:
```
cd pyleetcode
python manage.py runserver 0.0.0.0:8080
```

## Step 5: view the web site
open web browser, navigate to http://localhost:8080/, you should see the index page showing "Hello PyLeetCode Team!"
