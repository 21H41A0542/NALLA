 IBPS Scraper and Django API
- Setup
    - Clone the repository: git clone <repo_link>
    - Install dependencies: pip install -r requirements.txt
- Running Scripts
    - IBPS Scraper: python ibps_scraper/scraper.py
    - Django API: python django_api/manage.py runserver
- Testing API
    - Import Postman collection: login_api_test.json
    - Send POST request to http://localhost:8000/api/login/ with JSON body: {"username": "your_username", "password": "your_password"}