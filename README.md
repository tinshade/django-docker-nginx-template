# Django-Docker-NGINX Starter Template

This starter template comes with pre-configured docker container settings for development and production environments along with working implementation of serving static files via the NGINX proxy server, maintaining best practice.

The docker base image is **Python 3.8.0 Alpine** to make it as light-weight as possible.

## Usage

 1. Using Python 3.8, run `python -m venv env` to create a virtual environment
 2. Run `pip install -r requirements.txt` to install dependencies
 3. Run `cd app/` to change to `app/`
 3. Run `python manage.py runserver` to start development server
 4. Navigate to [http://127.0.0.1:8000](http://127.0.0.1:8000) to test
