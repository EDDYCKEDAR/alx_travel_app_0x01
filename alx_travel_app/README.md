# ALX Travel API

This project implements a RESTful API for managing property listings and bookings using Django REST Framework. It supports full CRUD operations and includes Swagger documentation for easy API exploration.

## Features

- CRUD API endpoints for Listings and Bookings
- User-friendly Swagger UI for API documentation and testing
- RESTful design with DRF ViewSets and routers
- Integrated with Django authentication system

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/EDDYCKEDAR/alx_travel_app_0x01.git
   cd alx_travel_app_0x01
2. Create and activate virtual environment
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
3. Install dependencies
   pip install -r requirements.txt
4. Apply migrations
   python manage.py migrate
5. Create superuser (optional for admin access)
   python manage.py createsuperuser
6. Run development server
   python manage.py runserver

Project Structure
listings/models.py: Django models for Listings and Bookings

listings/serializers.py: DRF serializers

listings/views.py: ViewSets for API endpoints

listings/urls.py: Router URL config for API

alx_travel_app/urls.py: Main project URL config including Swagger

Dependencies
Django

Django REST Framework

drf-yasg (Swagger generation)

License
This project is licensed under the MIT License.
