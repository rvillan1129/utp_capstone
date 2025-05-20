## How-To: Clone & Run Project

### Windows

```powershell
# create virtual environment
py -m venv .venv

# activate virtual environment
.venv/Scripts/activate

# install required packages
pip3 install -r .\requirements.txt

# initialize database 
python manage.py migrate

# start server
python manage.py runserver

```

### Mac

```bash
# create virtual environment
$ python3 -m venv .venv

# activate virtual environment
$ source .venv/bin/activate

# install required packages
$ pip3 install -r ./requirements.txt

# initialize database 
$ python manage.py migrate

# start server
$ python manage.py runserver

```
## Environment Variables

### Mac
```bash
# project searches for project-level .env file
```

## create superuser

### Mac & Windows
```bash
$ python manage.py createsuperuser
```