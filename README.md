# School Management System

![Developed by Revanta Biswas & Saarthak Shivam](https://img.shields.io/badge/Developed%20By%20%3A-Revanta%20Biswas%20&Saarthak%20Shivam-red)

---

## Functions

### Teacher
- Teachers apply for a job and, upon selection, their accounts are created and approved by the admin.
- After approval, teachers can access their dashboard.
- Teachers can take attendance for any class and view attendance records.
- Teachers can publish and announce notices to students, such as assignment submission deadlines.

### Student
- Students apply for admission/signup.
- Once their account is approved by the admin, students can access their dashboard.
- After approval, students can view their own details, such as attendance.
- Students cannot view other students' attendance or make announcements; they can only view them.

### Admin
- Admins sign up for an account.
- After logging in, admins can see the list of students/teachers applying for admission/jobs.
- Admins can approve or reject requests.
- Admins can update the details of any student/teacher.
- Admins can also announce notices.

## Drawbacks
- On the update page for teachers/students, the password must be updated.
- Anyone can become an admin.

## How to Run This Project

1. Install Python (3.7.6) (Ensure "Add to Path" is checked during installation).
2. Open Terminal and execute the following command:
   ``` 
   python -m pip install -r requirements.txt 
   ```
3. Download and extract the project zip folder.
4. Navigate to the project folder in Terminal and run the following commands:
   ```
   py manage.py makemigrations
   py manage.py migrate
   py manage.py runserver
   ```
5. Open your browser and enter the following URL:
   ```
   http://127.0.0.1:8000/
   ```

## Changes Required for the Contact Us Page

1. In `settings.py`, provide your email and password:
   ```
   EMAIL_HOST_USER = 'youremail@gmail.com'
   EMAIL_HOST_PASSWORD = 'your email password'
   EMAIL_RECEIVING_USER = 'youremail@gmail.com'
   ```
2. Log in to Gmail with the host email ID in your browser and enable the necessary settings.
   
