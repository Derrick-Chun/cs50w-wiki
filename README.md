# CS50W Project 1 – Wiki

This is my solution for Project 1 of Harvard's CS50 Web Programming with Python and JavaScript course.

The project is a Wikipedia-like encyclopedia built using Django. Users can view, search for, create, edit, and randomly browse Markdown-based encyclopedia entries. All content is stored locally and rendered as HTML.

## Features

- Browse all available entries from the homepage
- Search by exact title or keyword substring
- View detailed entry pages (Markdown converted to HTML)
- Create new entries with Markdown formatting
- Edit existing entries through a pre-filled form
- Get a random entry with one click
- Custom error page for invalid entries

## Technologies

- Python
- Django
- Markdown2

## Installation

To run locally:

1. Clone the repository  
   `git clone https://github.com/Derrick-Chun/cs50w-wiki.git`

2. Navigate to the project folder  
   `cd cs50w-wiki`

3. Create and activate a virtual environment  
   `python3 -m venv env`  
   `source env/bin/activate`

4. Install requirements  
   `pip install -r requirements.txt`

5. Run the server  
   `python manage.py runserver`

6. Visit `http://127.0.0.1:8000/` in your browser

## Final Notes

This project was part of CS50W and taught me how to work with Django views, URL routing, forms, and basic frontend templating. I also learned how to convert Markdown to HTML securely and handle user inputs through Django forms.
