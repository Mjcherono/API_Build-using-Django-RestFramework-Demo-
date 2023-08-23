# API_Build-using-Django-RestFramework-Demo-
Welcome to the Drinks App API project! 
This repository demonstrates building a simple API for managing drinks and their descriptions using Django Rest Framework.

### Features
- CRUD operations (Create, Read, Update, Delete) for drinks and their descriptions.
- Utilizes Django Rest Framework for streamlined API development.
- Follows RESTful design principles for consistent and intuitive endpoints.

### Installation
1. Clone the repository using:
   ```bash
   git clone https://github.com/YourUsername/API_Build-using-Django-RestFramework-Demo-.git

### Navigate to the dir
   cd API_Build-using-Django-RestFramework-Demo-

### Create a virtual environment
python -m venv venv
source venv/bin/activate

### Install dependencies
pip install -r requirements.txt

### set up db
python manage.py migrate

### Usage
#### Start the django development server
python manage.py runserver

Access the API endpoints through your web browser or an API client like Postman at http://127.0.0.1:8000/api/drinks/.

### API Endpoints
GET /api/drinks/: Retrieve a list of all drinks.
GET /api/drinks/<id>/: Retrieve a specific drink by ID.
POST /api/drinks/: Create a new drink.
PUT /api/drinks/<id>/: Update a drink by ID.
DELETE /api/drinks/<id>/: Delete a drink by ID.
