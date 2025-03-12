**Study Room Web App**

A Django-based web application designed to create collaborative study rooms where users can join, create groups, and send messages in real-time.

**Features**
User Authentication: Secure sign-up and login using email and password.
Create & Join Rooms: Users can create rooms around various topics, or join existing rooms to collaborate.
Real-time Messaging: Each room has a messaging system for users to communicate.
User Profiles: Users can customize their profile with an avatar, bio, and personal information.
Search Functionality: Search rooms by topic or name, making it easier to find relevant study groups.
Activity Feed: See recent activity and messages across the platform.
Tech Stack
Backend: Django (Python)
Frontend: HTML, CSS, JavaScript
Database: SQLite (or your preferred database)
Authentication: Django's built-in user authentication system
Deployment: Can be deployed on platforms like Heroku, DigitalOcean, or similar.
Installation

**_Clone the repository_**:

git clone https://github.com/yourusername/study-room-app.git
cd study-room-app

**_Create a virtual environment and activate it_**:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

**_Install the required dependencies_**:

pip install -r requirements.txt

**_Run migrations to set up the database_**:

python manage.py migrate

**_Create a superuser to access the Django admin panel_**:

python manage.py createsuperuser

**_Start the development server_**:

python manage.py runserver

The app will be running at http://127.0.0.1:8000/.

**Usage**
Create a new account or login using email and password.
Create a new room or join existing rooms to engage in study groups.
Send and receive messages in real-time with other participants in the room.

Screenshots
<img width="1440" alt="Screenshot 2025-03-12 at 02 36 19" src="https://github.com/user-attachments/assets/44a30946-495f-44f0-8c89-ab34bfacaf9b" />

**Contributing**
Feel free to fork the repository, make improvements, or submit pull requests. Any contributions are welcome!

