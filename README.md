# Django CRM Web Application

## Overview
Django CRM is a web-based customer relationship management system built using Django and Bootstrap. It allows businesses to manage customer interactions, track leads, and organize sales data efficiently.

## Features
✅ User authentication (Login, Logout)  
✅ Customer & Lead management  
✅ Dashboard 
✅ Role-based access control  

## Technologies Used
- Django  
- PostgreSQL   
- Bootstrap  
- Django Authentication System  

## Installation

### Prerequisites
Ensure you have Python (>= 3.8) and pip installed.

### 1. Clone the Repository
```sh
git clone https://github.com/muaadh-adeniyi/Django-CRM.git
cd django-crm
```

### 2. Create and Activate a Virtual Environment
For Windows (CMD):
```sh
python -m venv venv
venv\Scripts\activate
```
For macOS/Linux:
```sh
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Configure Database
Apply migrations:
```sh
python manage.py migrate
```
(Optional) Create a superuser:
```sh
python manage.py createsuperuser
```

### 5. Run the Development Server
```sh
python manage.py runserver
```
Visit **http://127.0.0.1:8000/** in your browser.

## Usage
- Register/Login as a user  
- Add and manage customers and leads  
- Track sales progress  

## Contributing
Pull requests are welcome. For major changes, please open an issue first.

## License
This project is licensed under the MIT License.
