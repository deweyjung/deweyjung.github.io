---
title: python project structure
date: 2020-01-09 09:14:10
tags: python
categories:
	- 00. Python
	- 00. Project Structure
---
General ::

$PROJECT_ROOT
 ├─ README.rst
 ├─ docs
 ├─ rsc
 ├─ src
 │  ├─ packagae
 │  │   ├─ __init__.py
 │  │   └─ ...
 │  └─ main.py ....
 ├─ tests
 │  ├─ package
 │  │   └─ ...
 |  └─ test_main.py
 └─ setup.py

REF : https://trowind.tistory.com/105



Flask :: 

flaskr/
│
├── flaskr/
│   ├── ___init__.py
│   ├── db.py
│   ├── schema.sql
│   ├── auth.py
│   ├── blog.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── auth/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   │
│   │   └── blog/
│   │       ├── create.html
│   │       ├── index.html
│   │       └── update.html
│   │ 
│   └── static/
│       └── style.css
│
├── tests/
│   ├── conftest.py
│   ├── data.sql
│   ├── test_factory.py
│   ├── test_db.py
│   ├── test_auth.py
│   └── test_blog.py
│
├── venv/
│
├── .gitignore
├── setup.py
└── MANIFEST.in

REF : https://realpython.com/python-application-layouts/

