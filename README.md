# Online Quiz
>[Khalid Ali] https://github.com/Alikhalid2020
  
# Description  

This is an online study where where one can take quizes and get marked from teachers

##  Live Link  
 Click [View Site]()  to visit the live-site
  
## User stories
As a user, I would like to:

* number of students
* quizes to take
* gets your marks
* Search for projects 
* as a teacher see number of student
* as a teacher i would be able to create assignments


### Admin

- Create Admin account using command
```
python manage.py createsuperuser

```
- After Login, can see Total Number Of Student, Teacher, Course, Questions are there in system on Dashboard.
- Can View, Update, Delete, Approve Teacher.
- Can View, Update, Delete Student.
- Can Also See Student Marks.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Teacher

- Apply for job in System. Then Login (Approval required by system admin, Then only teacher can login).
- After Login, can see Total Number Of Student, Course, Questions are there in system on Dashboard.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.
> **_NOTE:_**  Basically Admin Will Hire Teachers To Manage Courses and Questions.

### Student

- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can See How Many Courses/Exam And Questions Are There In System On Dashboard.
- Can Give Exam Any Time, There Is No Limit On Number Of Attempt.
- Can View Marks Of Each Attempt Of Each Exam.
- Question Pattern Is MCQ With 4 Options And 1 Correct Answer.
---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements. txt

```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```



