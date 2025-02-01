# Opinion App

## Overview
The Opinion App is a full-stack web application built using Django and Django Tailwind. It allows users to sign up, log in, and share their thoughts through tweets. The platform provides essential CRUD (Create, Read, Update, Delete) operations for user-generated tweets.

## Features
- **User Authentication:** Secure user registration, login, and logout.
- **Tweet CRUD:** Create, read, update, and delete tweets.
- **Responsive Design:** Seamless experience across desktop and mobile devices using Tailwind CSS.

## Tech Stack
- **Backend:** Django (Python)
- **Frontend:** Django Tailwind, HTML, CSS, JavaScript
- **Database:** SQLite (default) or PostgreSQL for production
- **Deployment:** Compatible with platforms like Heroku and AWS

## Installation

### Prerequisites
- Python 3.x
- Virtualenv (optional but recommended)

### Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd opinion-app
   ```

2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Install and configure Django Tailwind:
   ```bash
   python manage.py tailwind install
   python manage.py tailwind build
   ```

5. Apply migrations:
   ```bash
   python manage.py migrate
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

7. Open your browser and navigate to `http://localhost:8000`.

## Usage
- Register or log in to your account.
- Create, read, update, and delete tweets.

## Deployment
1. Set environment variables for production, including `SECRET_KEY`, `DEBUG`, and database settings.
2. Use a production-ready web server (e.g., Gunicorn) and configure static file handling.
3. Deploy on cloud services like Heroku, AWS, or DigitalOcean.

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature/new-feature`).
3. Commit your changes and push them.
4. Create a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or support, please contact [sudsingh32@gmail.com].

