# Book Cover – Fundamentals of Web Application Development

## Overview
This project includes a book cover design created with HTML and CSS and a Django wrapper for serving the page locally.

## Files
- `index.html` — Main static HTML page
- `style.css` — Stylesheet
- `author-photo.jpg` — Author image used on the cover
- `bookcover/` — Django project folder
- `cover/templates/cover/index.html` — Django template version of the page
- `manage.py` — Django management script

## How to Run
### Static version
1. Place your author photo in this folder and rename it to `author-photo.jpg`.
2. Open `index.html` in any web browser.

### Django version
1. Install Django if needed: `python -m pip install django`
2. Run: `python manage.py runserver`
3. Open `http://127.0.0.1:8000/` in your browser.

## Design Steps
1. Create a Django project.
2. Add a Django app for the cover page.
3. Place the HTML template in `cover/templates/cover/index.html`.
4. Use `style.css` for page styling.
5. Add `author-photo.jpg` for the author image.
6. Update the text and layout as needed.

## Notes
- Replace `author-photo.jpg` with your own image file to customize the author photo.
- To change the author name or other text, edit `cover/templates/cover/index.html` or `index.html`.
