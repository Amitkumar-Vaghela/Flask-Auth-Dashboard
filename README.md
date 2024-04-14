![User Registration Form](https://github.com/Amitkumar-Vaghela/Flask-Auth-Dashboard/blob/master/HTMLpageServedBy%20Flask.png)

![User Registration Form](https://github.com/Amitkumar-Vaghela/Flask-Auth-Dashboard/blob/master/registrationpng.png)



##Flask Auth Dashboard
Flask Auth Dashboard is a web application built using Flask, providing user authentication and a dashboard interface.

##Features
User registration and login functionality
Secure password storage using hashing
Dashboard interface for authenticated users

##Installation

1.Clone the repository:
git clone https://github.com/Amitkumar-Vaghela/Flask-Auth-Dashboard.git

2.Navigate to the project directory:
cd Flask-Auth-Dashboard

3.Install dependencies:
pip install -r requirements.txt

##Usage

1.Set up the database:
Ensure you have SQLite installed, or configure the `SQLALCHEMY_DATABASE_URI` in `app.py` to use a different database.
Run the following commands to create the database tables:
flask db init
flask db migrate
flask db upgrade

2.Run the Flask application:
flask run

3.Access the application in your web browser at http://127.0.0.1:5000/

##Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues if you encounter any problems.

##License
This project is licensed under the MIT License - see the LICENSE file for details.



