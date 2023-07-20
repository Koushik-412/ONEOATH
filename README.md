MYSCHOOL PROJECT

This app is meant to be used by school manager to manage their school records and exam results

Project contains the 3 roles:
1)Admin
2)Teacher staff
3)student data
4) results and finances.

- Admin Users Can:
  - Access overall summary charts for students' performances, staff performances, courses, subjects, leave, etc.
- Administer staff by adding, updating, and deleting their records.
- Handle student management, including adding, updating, and deleting student records.
- Control course details by adding, updating, and deleting courses.
- Manage subjects by adding, updating, and deleting subject information.
- Handle sessions by adding, updating, and deleting session records.
- View student attendance records.
- Respond to student/staff feedback and communicate with them.
- Review and make decisions on student/staff leave requests (approve or reject).


- Staff/Teachers Can:
  - See overall summary charts related to their students, subjects, leave status, etc.
  - Take/update students' attendance
  - Add/update results
  - Apply for leave
  - Send feedback to HOD (Head of the Department)

- Students Can:
  - See overall summary charts related to their attendance, subjects, leave status, etc.
  - View attendance
  - View results
  - Apply for leave
  - Send feedback to HOD (Head of the Department)

HOW TO RUN THE PROJECT:

username: koushik
password:koushik

Usage:
Install in a Virtual Environment. Once you have set up a VE, clone this project

git clone https://github.com/adigunsherif/Django-School-Management-System.git
Then

cd Django-School-Management-System
Run:

pip install -r requirements.txt #install required packages
python manage.py migrate # run first migration
python manage.py runserver # run the server
Then locate http://172.0.0.1:8000

Note:Only admin can add the students and staff 

Admin Login
When you run migrate, a superuser is created.:
YOU CAN ASLO CREATE SUPERUSER: python manage.py createsuperuser
username: koushik
password: koushik
Roadmap
To build a fully fledged open source school management.
