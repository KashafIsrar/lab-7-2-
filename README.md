# lab-7-2-
# **Cooking Chronicles**

Welcome to **Cooking Chronicles**, a Flask-based web application where every recipe tells a story! This project allows users to explore recipes, learn about our services, and join our community through registration and login.

---

## **Features**
1. **Homepage**
   - Welcomes users with an engaging hero section and information about the website.
   - Includes navigation to all other pages.

2. **About Us**
   - Provides details about the organization and its mission.

3. **Recipes**
   - A dedicated page showcasing a variety of recipes.

4. **Login & Registration**
   - Allows users to log in or sign up to access exclusive content.

5. **Contact Us**
   - Enables users to reach out for assistance or inquiries.

6. **Services**
   - Displays the services offered, including custom recipe development and online cooking classes.

---

## **Installation and Setup**
Follow these steps to set up and run the project on your local machine:

### **1. Clone the Repository**
Use the following command to clone the repository:
```bash
git clone https://github.com/your-username/cooking-chronicles.git
cd cooking-chronicles
2. Set Up a Virtual Environment
Create and activate a virtual environment:

bash
Copy code
# On macOS/Linux
python3 -m venv venv
source venv/bin/activate

# On Windows
python -m venv venv
venv\Scripts\activate
3. Install Dependencies
Install the required packages using pip:

bash
Copy code
pip install -r requirements.txt
4. Run the Application
Start the Flask development server:

bash
Copy code
python app.py
5. Access the Application
Open your web browser and go to:

arduino
Copy code
http://127.0.0.1:5000/
File Structure
php
Copy code
cooking-chronicles/
│
├── app.py                  # Main application file
├── templates/              # HTML files for the Flask app
│   ├── home.html
│   ├── about.html
│   ├── recipies.html
│   ├── login.html
│   ├── registration.html
│   ├── contact.html
│
├── static/                 # Static files
│   ├── styles.css          # CSS styles
│   ├── img/                # Images folder
│       ├── cooklogo.jpg
│       ├── cook3.jpeg
│       ├── cook4.jpeg
│       ├── food7.jpeg
│
├── requirements.txt        # Project dependencies
├── README.md      
