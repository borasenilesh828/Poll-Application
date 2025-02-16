# Poll-Application
Developed a basic poll application using the Django framework, enabling users to view polls, cast votes, and see real-time results. Integrated an admin panel for managing polls, allowing easy addition, editing, and deletion of questions and choices. Utilized SQLite3 as the database for efficient data storage and implemented Django's built-in authentication for secure admin access. The application follows MVC architecture, ensuring clean and scalable code. Enhanced UI with Django templates and Bootstrap for a user-friendly experience. Designed RESTful APIs to handle voting operations efficiently. Optimized database queries to improve performance and ensure smooth user interactions.

Features 🚀
View active polls and vote
See real-time voting results
Admin panel for managing polls (add, edit, delete questions/choices)
Secure admin authentication using Django’s built-in system
Uses SQLite3 as the database
Clean UI with Django templates and Bootstrap.

Technologies Used 🛠️
Backend: Python, Django Framework
Frontend: HTML, CSS, Bootstrap, Django Templates
Database: SQLite3
API: Django’s built-in ORM and RESTful structure.

Installation & Setup 🏗️
1. Clone the Repository
git clone https://github.com/borasenilesh828/poll-application.git

2. Create & Activate a Virtual Environment
python -m venv venv
source venv/bin/activate
# On Windows: venv\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

4. Apply Migrations
python manage.py migrate

5. Create Superuser (For Admin Panel Access)
python manage.py createsuperuser

7. Run the Server
python manage.py runserver
Access the app at http://127.0.0.1:8000/ and the admin panel at http://127.0.0.1:8000/admin/.

Usage 👨‍💻
Users can view and vote on polls.
Admins can create, edit, and delete polls via the admin panel.
Voting results update in real-time.


Contributing 🤝
Feel free to contribute by submitting a pull request!

License 📜
This project is licensed under the MIT License.
Copytight by @Nilesh Borase.
