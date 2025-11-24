VNS Banking (Django Application)
This is a VNS Banking application developed using Django, an open-source Python-based web framework.
Installation and Setup
1. First, ensure Python is installed by checking the version in your terminal: python --version (or python3 --version).
2. Install Django using PIP: pip install Django.
3. Start a new Django project: django-admin startproject <project_name>.
4. Open an integrated terminal inside your project folder.
5. Create an app for your project: python manage.py startapp <app_name>.
6. Integrate MySQL by installing the necessary client: pip install mysqlclient.
7. Configure the database settings: In your project's settings.py file, find the DATABASES section and update the ENGINE to django.db.backends.mysql. Then, enter your MySQL username and password.

Features

-- Once the setup is complete, you can start the application and see the home page with options to log in or create a new account.
-- Secure Authentication: When users create an account and log in, their password is encrypted for security, so it cannot be viewed or tracked.
-- Access Control: After logging in, users with the correct credentials can view customer information, transactions, loans, and account statements.
-- PDF Generation: The application also has a feature to generate a PDF for a user's statements.


