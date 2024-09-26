# Web Scraping Application with Django and BeautifulSoup

## Overview

This project is a web application that allows users to scrape data from websites and download the extracted information in various formats such as CSV, JSON, and PDF. The app is built using Django for the backend and BeautifulSoup for the scraping functionality.

## Features

- **Data Extraction**: Scrapes data such as titles, headings, and paragraphs from websites.
- **Multiple Download Formats**: Users can download the extracted data in CSV, JSON, and PDF formats.
- **User-Friendly Interface**: Easy-to-use form for entering the URL to scrape and selecting the download format.
- **Efficient Scraping**: Uses BeautifulSoup for HTML parsing and data extraction.
  
## Technologies Used

- **Backend**: Django, Python
- **Frontend**: HTML, CSS
- **Web Scraping**: BeautifulSoup
- **Data Export**: CSV, JSON, PDF formats

## Installation

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine
- `pip` for Python package management
- A virtual environment tool like `venv` (optional but recommended)

### Steps

1. Clone the repository:

git clone https://github.com/your-username/web-scraping-app.git
   
2. Navigate into the project directory:
   
cd web-scraping-django-app

3.Create a virtual environment (optional but recommended):

python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

4.Install the required packages:

pip install -r requirements.txt

5.Apply migrations to set up the database:

python manage.py migrate

6.Run the Django development server:

python manage.py runserver

## Open a browser and navigate to http://127.0.0.1:8000/ to access the application.

