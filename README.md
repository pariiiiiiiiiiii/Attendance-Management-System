## ATTENDANCE MANAGEMENT SYSTEM

Project is build using Flask , python framework and SQLITE  as the database .
The System allow professor to mark attendance of the student for different classes , divisions.

Technology Used - 
   - HTML , CSS and Boothstrap  for Frontend
   - Python , Flask and SQLite for Backend

Features -
   - Login - Only Professor can log in to system for marking attendance
   - Attendance Marking - Professors can marks attendance for student for specific date, course and divison also professor can add and remove student .
   - Report - professor can view monthly attendance report of every student.
   - Design - Design is made speficaly where it looks good on all the screen sizes.
## Steps to Run the Project

### 1. Clone the Repository

First, clone the repository to your local machine:

bash
git clone https://github.com/your-username/attendance-system.git
cd attendance-system


### 2. Set Up the Virtual Environment

It's recommended to use a virtual environment to manage dependencies. If you don't have virtualenv installed, you can install it using pip:

```bash
pip install virtualenv


Create a virtual environment:

```bash
virtualenv venv


Activate the virtual environment:

- On Windows:

  ```bash
  venv\Scripts\activate
  
  

### 3. Install Dependencies

Install the required Python libraries:

```bash
pip install -r requirements.txt


### 4. Set Up the Database

The project uses SQLite, and the database will be automatically created when you run the app. However, you can manually create the database tables by running the following command:

```bash
python
>>> from app import db
>>> db.create_all()


This will create the necessary tables in the SQLite database (attendance.db).

### 5. Run the Application

To start the Flask development server, run the following command:

```bash
python app.py


The application will be available at http://127.0.0.1:5000/ in your browser.

### 6. Access the Application

- *Login*: Use the default professor credentials to log in:
  - Username: root
  - Password: root

- *Dashboard*: After logging in, you will be redirected to the dashboard where you can manage attendance.

### 7. Testing the Application

Once the application is running, you can:

- Add students to the system.
- Mark attendance for students in a specific division.
- View monthly attendance reports for each student.

### 8. Stop the Application

To stop the application, press Ctrl+C in the terminal where the server is running.

## Folder Structure


attendance-system/
│
├── app.py                # Main application file
├── requirements.txt      # List of Python dependencies
├── templates/            # HTML templates for rendering pages
│   ├── add_student.html  # page to add students in the database
│   ├── dashboard.html    # Dashboard page
│   ├── login.html        # Login page
│   ├── students.html     # Page to view students
│   ├── attendance.html   # Page to mark attendance
│   ├── base.html         # Base template for common layout
|   └── report.html       # Page to view attendance reports
├── static/               # Static files (CSS, JS, images)
├── attendance.db         # SQLite database file (auto-generated)
└── README.md             # Project documentation






  
 
     


