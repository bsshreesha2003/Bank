# ICICI Bank Customer Registration Portal

This is a Django-based web application for registering customers with ICICI Bank and allowing them to open various types of accounts such as Savings, Mutual Fund (MF), and Loan accounts.

## Features

- Customer Registration with auto-generated Customer ID starting from `CID_5001`.
- Options for customers to open Savings, MF, and Loan accounts.
- Admin interface for managing and viewing entries.
- Easy setup and deployment.

## Requirements

- Python 3.x
- Django 3.x or higher
- SQLite (default database for Django)

## Setup Instructions

### 1. Clone the Repository

```sh
git clone [https://github.com/Final_FSD.git](https://github.com/bsshreesha2003/Bank.git)
cd Final_FSD

python -m venv icici
source icici/bin/activate  # On Windows, use `icici\Scripts\activate`

python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
