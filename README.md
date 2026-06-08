# Threat-Detection-Using-Machine-Learning-Techniques
# Threat Detection Using Machine Learning

## Overview

Threat Detection Using Machine Learning is a web-based Network Intrusion Detection System (NIDS) developed using Django and Python machine learning libraries. The application enables users to analyze security events and classify cyber attacks using trained machine learning models.

The platform incorporates a user authentication system, allowing registered users to securely access threat detection features and monitor attack classifications through a web interface.

## Features

### Security Detection

* Detection and classification of cyber attacks
* Machine learning-powered threat analysis
* Support for SQL Injection (SQLi), Cross-Site Scripting (XSS), and Nmap Xmas Scan detection
* Incident classification using multiple machine learning algorithms
* Real-time prediction through a web dashboard

### Machine Learning Models

* Random Forest
* AdaBoost
* Naive Bayes

## Technology Stack

### Backend

* Python
* Django

### Machine Learning

* Scikit-learn
* Pandas
* NumPy

### Frontend

* HTML
* CSS
* Bootstrap
* JavaScript

### Database

* SQLite

## Attack Types Detected

* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Nmap Xmas Scan
* Network Reconnaissance Activities
* Additional attack categories from the training dataset

## System Workflow

1. User logs into the application.
2. Security-related data is submitted for analysis.
3. Features are extracted from the dataset.
4. Machine learning models process the input.
5. The system predicts and classifies the attack type.
6. Results are displayed through the dashboard.

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/threat-detection-ml.git
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Database Migrations

```bash
python manage.py migrate
```

### Create Admin User

```bash
python manage.py createsuperuser
```

### Start the Development Server

```bash
python manage.py runserver
```

### Access the Application

Open your browser and visit:

```text
http://127.0.0.1:8000
```

## Screenshots

### Login Page

Add screenshot here.

### Dashboard

Add screenshot here.

### Threat Detection Results

Add screenshot here.

### User Profile

Add screenshot here.

## Learning Outcomes

* Applied machine learning techniques for cybersecurity applications.
* Developed a Django-based web application with authentication.
* Implemented intrusion detection and attack classification models.
* Gained practical experience in threat analysis and security monitoring.
* Improved understanding of web application development and secure user management.

## Future Enhancements

* SIEM integration
* Real-time packet capture
* Threat intelligence feeds
* Deep learning-based detection models
* Automated alert generation

## Author

Yogeeswaran D

