# personal-portfolio-2.0

## Installation
### Linux
```bash
git clone https://github.com/NikiDeyanov86/personal-portfolio-2.0.git
cd personal-portfolio-2.0
pip install virtualenv
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```
### Windows
```bash
git clone https://github.com/NikiDeyanov86/personal-portfolio-2.0.git
cd personal-portfolio-2.0
pip install virtualenv
python -m virtualenv venv
venv\scripts\activate
pip install -r requirements.txt
```

## Run
### Linux
```bash
export FLASK_ENV=production
flask run
```
### Windows
```bash
set FLASK_ENV=production
flask run
```