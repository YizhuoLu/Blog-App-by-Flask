===============
Blog App Flaskr
===============
Run
===
- $ export FLASK_APP=flaskr
- $ export FLASK_EVN=development
- $ flask init-db
- $ flask run
Open http://127.0.0.1:5000 in a browser.
----------------------------------------
Test
====
- $ pip install '.[test]'
- $ pytest
Run with coverage report:
-------------------------
- $ coverage run -m pytest
- $ coverage report
- $ coverage html # open htmlcov/index.html in a browser