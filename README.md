## Prerequisites

Before you begin, make sure you have the following installed on your machine:

- Python (version 3.8 or higher)
- pip (Python package installer)

## Installation

### 1. Clone the Repository

Clone the repository to your local machine using Git:

```bash
git clone https://github.com/Robben1972/Demo_Instagram.git
cd repo-name
```

### 2. Set Up a Virtual Environment

It's recommended to use a virtual environment to manage your project's dependencies:

```bash
python -m venv venv
```

Activate the virtual environment:

- On Windows:
  ```bash
  venv\Scripts\activate
  ```
- On macOS and Linux:
  ```bash
  source venv/bin/activate
  ```

### 3. Install Dependencies

Install all required dependencies using pip:

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

Run the following commands to apply migrations and set up the database schema:

```bash
python manage.py migrate
```

## Running the Project

Once everything is set up, you can run the Django development server with the following command:

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your web browser to see the project running.

## Create a Superuser

To create a superuser (an admin account for accessing the Django admin panel), run the following command:

```bash
python manage.py createsuperuser
```

You will be prompted to enter a username, email, and password.
