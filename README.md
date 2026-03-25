# Django CRUD App

A simple Django web application to perform CRUD (Create, Read, Update, Delete) operations on member records.

## Features

- Add new members with first name, last name, email, and contact number
- View all members
- Update existing member details
- Delete members

## Tech Stack

- Python
- Django 5.2
- SQLite (default database)

## Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/samarthverma4/DjangoCrudApp.git
   cd DjangoCrudApp
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Start the server**
   ```bash
   python manage.py runserver
   ```

6. Open http://127.0.0.1:8000/ in your browser.
