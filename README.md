# Full Stack Cloud Development Capstone Project

## Overview

This project is a full-stack web application developed using Django for the backend, Django templates for the frontend, and integration with IBM Cloud Functions and Cloudant. The system simulates a car dealership platform that allows managing dealerships, reviews, and dynamically displaying vehicle and dealer information.

## Key Features

- Robust backend system built with Django, including models, views, and REST APIs.
- Dynamic web interface using Django templates for navigation and interaction.
- Integration with IBM Cloud Functions for serverless capabilities.
- Use of Cloudant NoSQL database to store dealership and review data.
- Docker containerization to facilitate cloud deployment.
- Configuration for deployment on Kubernetes and IBM Cloud Code Engine.
- User authentication, registration, login, and management features.

## Project Structure

- `/server`: Main Django application source code.
  - `/djangoapp`: Django app containing models, views, templates, and URLs.
  - `/djangobackend`: Django project configuration files.
  - `/static`: Static files including CSS, JavaScript, and images.
  - Deployment configuration files (Dockerfile, deployment.yaml, etc).

- `/functions`: Serverless functions written in Python and JavaScript for IBM Cloud Functions integration.

- `/cloudant/data`: JSON datasets for importing into Cloudant database.

- Detailed documentation provided in `.md.html` and PDF files to guide project usage and development.

## Technologies Used

- Python 3.x, Django Framework  
- JavaScript (for serverless functions)  
- IBM Cloud Functions and Cloudant  
- Docker and Kubernetes  
- HTML5, CSS3 for frontend  

## Estimated Development Time

The project, built upon existing code and templates, was completed in approximately 16 hours as part of an IBM course, focusing on adaptation, integration, and deployment of features.

## How to Run

1. Clone this repository:

```bash
git clone <YOUR_REPOSITORY_URL>
````

2. Set up Python environment and install dependencies:

```bash
cd server
python -m venv venv
source venv/bin/activate      # Linux/MacOS
venv\Scripts\activate         # Windows
pip install -r requirements.txt
```

3. Configure environment variables and credentials for IBM Cloud services (Cloudant, Functions).

4. Run migrations and start the Django server:

```bash
python manage.py migrate
python manage.py runserver
```

5. Access the application in your browser at `http://localhost:8000`.

## Documentation and Support

Complete documentation, usage guides, and checklists are included in the project folder, with PDF and HTML files to assist in understanding and maintenance.

## License

Specify the project license here (e.g., MIT, Apache 2.0, etc).