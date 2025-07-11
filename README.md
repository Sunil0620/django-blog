# Django Blog

A simple blog application built with Django.

## Features

- Create, read, update, and delete blog posts
- User authentication and authorization
- Clean and responsive design
- Admin interface for content management

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd django-blog
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install django
   ```

4. Run migrations:

   ```bash
   python manage.py migrate
   ```

5. Create a superuser (optional):

   ```bash
   python manage.py createsuperuser
   ```

6. Start the development server:

   ```bash
   python manage.py runserver
   ```

7. Open your browser and navigate to `http://127.0.0.1:8000/`

## Project Structure

- `blog/` - Main blog application
- `myblog/` - Django project settings
- `templates/` - HTML templates
- `manage.py` - Django management script

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the MIT License.
