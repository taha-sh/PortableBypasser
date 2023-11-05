
# Portable Paywall Bypasser


This is a light web application that attempts to bypass paywalls by pretending to be a Google Bot.
It uses the cached up version of websites that search engine crawlers are permitted to access.

It doesn't work with every paywall, but you might get lucky ;).

This was made as a short research into paywalls. I am not responsible for how it's used.

## Getting Started
Python is required for this application to run and needs to be installed and a guide on how to do so can be found [here](https://realpython.com/installing-python/).

Flask is required as well and can (usually) be installed with:

``pip install flask`` or ```python -m pip install flask```,



## Installation

- Clone the repository:
```bash
git clone https://github.com/taha-sh/VTFlaskScan.git
cd VTFlaskScan
```
- Install Flask if you haven't already:
```pip install flask```

- Setup the Flask environment:

For UNIX-systems (Linux, MacOS):
```
export FLASK_APP=app.py
export FLASK_ENV=development
```
For Windows users:
```
set FLASK_APP=app.py
set FLASK_ENV=development
```
- Run the application:
```
flask run
```
The server should start, typically on http://127.0.0.1:5000/.

