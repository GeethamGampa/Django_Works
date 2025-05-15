#### Django_Works
Works on Django

#### Django_Works
Works on Django

#### Project Overview: EduTrack
A web application where:

- Students can log in and view their enrolled courses, attendance, grades, and feedback.
- Teachers can manage students, assign grades, and track progress.
- Admins can manage users, courses, and permissions via Django admin.

#### Main Features:
- Student Dashboard
- View enrolled courses
- Attendance and grades
- Feedback from teachers
- Teacher Dashboard
- View and manage student lists
- Add/edit attendance and grades
- Give comments or feedback
- Course Management
- Add/edit/delete courses
- Enroll students in courses
- Authentication
- Login/Logout for students and teachers
- Permissions based on role
- Admin Panel
 

#### Apps to Create:
students – manage student profiles, attendance, grades
courses – course list, enrollment
teachers – teacher profile, feedback
dashboard – landing pages and role-based dashboards


#### EduTrack Project Setup and Commands

1. Created virtual environment:  
   python -m venv Myenv

2. Activated virtual environment:  
      Myenv\Scripts\activate  
    
3. Installed Django:  
   pip install django

4. Checked Django version:  
   django-admin --version

5. Created Django project:  
   django-admin startproject EduTrack

6. Created app named 'students':  
   python manage.py startapp students

7. Added 'students' app to INSTALLED_APPS in EduTrack/settings.py

8. Created simple views in students/views.py

9. Created students/urls.py and linked URLs

10. Included students.urls in EduTrack/urls.py

11. Run server:  
    python manage.py runserver

12. Made migrations:  
    python manage.py makemigrations

13. Applied migrations:  
    python manage.py migrate


14. Pushed project to GitHub:  
    git init  
    created .gitignore  
    git add .  
    git commit -m "Initial commit"  
    git remote add origin  
    git push -u origin main







