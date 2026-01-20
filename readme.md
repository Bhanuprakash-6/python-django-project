# TweetBar 🐦 
**A Full-Stack Django Social Media Application**

TweetBar is a social networking platform where users can share their thoughts, upload images, and interact with a community. Built using Python and Django, this project demonstrates a complete implementation of CRUD operations, user authentication, and media management.

## 🚀 Features
- **User Authentication:** Secure Sign-up, Login, and Logout functionality using Django's built-in auth system.
- **Tweet Management (CRUD):** Users can create, read, update, and delete their own tweets.
- **Media Support:** Integrated image uploading for tweets using Django Media settings.
- **Permissions:** Restricted access—only authenticated users can create or edit content. Users can only edit/delete their own posts.
- **Aesthetic UI:** Styled with a modern, responsive interface (Tailwind CSS/Bootstrap).

## 🛠️ Tech Stack
- **Backend:** Python 3.x, Django 5.x
- **Frontend:** HTML5, CSS3, Tailwind CSS
- **Database:** SQLite (Default) / PostgreSQL 
- **Environment:** Python Virtual Environments (`venv`)

## 📦 Installation & Setup


note - in this i have replace the file name manage.py to m.py

1. **Clone the repository:**
   
   cd tweetbar

2. Create and activate a virtual environment:

Bash

python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate


3 .Install dependencies:

Bash

pip install -r requirements.txt


4. Run Migrations:

Bash

python manage.py makemigrations
python manage.py migrate


5. Create a Superuser (Admin Access):

Bash

python manage.py createsuperuser


6. Start the Development Server:

Bash

python manage.py runserver
Access the app at http://127.0.0.1:8000/

📂 Project Structure
tweet/: The main application logic (Models, Views, Forms).

templates/: HTML templates including the base layout and independent landing page.

static/: CSS and JavaScript assets.

media/: User-uploaded images.

🎓 Learning Credits
This project was built as part of my learning journey in Python-Django, inspired by the Chai aur Code series. It helped me master the Django Request-Response cycle, Template Inheritance, and Backend logic.


Developed by BHANUPRAKASH T
