# Base Project Structure

## Stack

Flask 
HTMX
DaisyUI + Tailwind CSS

## ORM

To Do

## Auth

To Do

## Deployment

To Railway 

## Directory Structure

project-root/
├── backend/
│   ├── app.py
│   ├── __init__.py
│   ├── auth/
│   │   ├── __init__.py
│   │   └── login.py
│   ├── templates/
│   │   ├── base.html
│   │   └── login.html
│   ├── static/
│   │   ├── css/
│   │   │   └── styles.css
│   │   ├── js/
│   │   │   └── scripts.js
│   │   └── img/
│   └── utils/
│       └── helpers.py
├── frontend/
│   ├── index.html
│   ├── components/
│   │   ├── header.html
│   │   └── footer.html
│   └── css/
│       └── custom_styles.css
├── tests/
│   ├── test_login.py
│   └── test_helpers.py
├── venv/ (not committed, virtual environment folder)
├── .gitignore
├── README.md
├── requirements.txt
└── tailwind.config.js