#kape_kanto

A multi-page Django website for a small neighborhood coffe and pastry shop
Final project for [Human Computer Interaction(ISAE-101)]

#Overview 

Kape Kanto is a simple shop website that lets customers see the menu,
the shop's story, photos, and contact details.

**Target users** customers who want to check the menu and opining hours.

## Features
-5 page: Home, About, Menu, Gallery, Contact
-Reusable base templates with navbar and footer includes
-Named URLs and '{%  url %}' navigation
-Static CSS and Images
-Responsive Design

## Django Concepts Used 
-Template inheritance ('{% extends %}', '{% block %})
-'{% url %}' with named URLs
-'{% load static %}' and '{% static %}'

## Setup


1. Clone the repository

'''
https://github.com/djangoproject09/kape_kanto.git
cd kape_kanto
'''

2. Create and activate a virtual environment:
'''
       CMD or VS Code
    python -m venv venv
    venv\Scripts\activate
'''

3. Install requirments:
'''
    pip install -r requirment.txt
'''

4. Run Migration:
'''
    python manage.py migrate
'''

5. run the server:
''' 
    python manage.py
'''

6. Open htpp://127.0.0.1:8000












