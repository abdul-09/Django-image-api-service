# Django Image API Service

Django Image API Service is a Django application that provides a RESTful API for managing and serving images. It is designed to be used as a backend service for image-related functionalities in web applications.

## Features

- Image upload with category support.
- Image metadata management (title, alt text, status).
- API endpoints for retrieving images and categories.

## Screenshot

![Screenshot (70)](https://github.com/abdul-09/Django-image-api-service/assets/114946911/bf93467b-4481-4f17-85e9-00e65f1f6ef5)


## Requirements

- Python 3.x
- Django 5.x
- Django REST framework

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/django-image-api-service.git
   cd django-image-api-service

## Install Dependencies
``` bash
pip install -r requirements.txt
```

## Apply migrations
``` bash
python manage.py migrate
```
## Run the development server
``` bash
python manage.py runserver
```

## Usage
API Endpoints
Images:

    - List all images: GET /api/images/
    - Retrieve a specific image: GET /api/images/<image_id>/
    - Upload a new image: POST /api/images/
Categories:

    - List all categories: GET /api/categories/
    - Retrieve a specific category: GET /api/categories/<category_id>/
