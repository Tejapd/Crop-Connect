#  Crop Connect Project

Crop Connect is an intelligent agricultural management system that uses machine learning to maximize farming choices. The system also incorporates a virtual market for organic products, facilitating communication between officials, sellers, and visitors, by combining soil nutrient analysis, rainfall data, crop recommendations, and yield forecasts.


##  Technologies Used
- Backend: Django, Python
- Frontend: HTML, CSS, JavaScript, Bootstrap
- Machine Learning:Models for crop recommendation and yield prediction

##  Key Features
- Soil & Rainfall Data: Provides comprehensive insights for better crop decisions.
- Crop Recommendation & Yield Prediction: Boosts crop yield by 20%.
- Virtual Market: Facilitates transactions and connects users for organic product sales.
- Secure Logout: Ensures safe user session management.

##  How to Run the Project

### Prerequisites
Python installed on your system.
Virtual Environment: Recommended to isolate dependencies.

### Setup

1. Clone the Repository:
   
   git clone https://github.com/Tejapd/Crop-Connect
   

2. Create a Virtual Environment:
   
   python -m venv env
   source env/bin/activate   # On Windows: `env\Scripts\activate`
   

3. Install Dependencies:
  
   pip install -r requirements.txt
   

4. Run Migrations:
  
   python manage.py makemigrations
   python manage.py migrate
   

5. Create a Superuser:
   
   python manage.py createsuperuser
   

6. Run the Development Server:
   
  python manage.py runserver
 

7. Access the Application:
   Open your browser and go to "http://127.0.0.1:8000/".




