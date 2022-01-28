# Mini-Project
<img width="949" alt="image" src="https://user-images.githubusercontent.com/55504424/151436697-45f66513-b889-4046-ac0a-a297b4d8bb9f.png">

## DESCRIPTION
1. 1st page will have 2 buttons , 1 for student and other for teacher.
2. if student button is pressed, it will take us to a session page( A session page will have multiple sessions started by multiple teachers).
  2a. In the session page, we will select the session of our teacher, then it will ask us to enter our registration number.
  2b. If the resgistration number is correct, then it will allow us to the anoter page.
  2c. In this new page, we will have options to open camera and take picture, once the pciture is clicked by the student, the system will notify the user
     Messages from the server could be: 
     a) Attendance Taken for {{Student Name}}.
     b) Invalid Picture, take the picture again.
     c) No such user in the database.
3. if teacher button is pressed, then it will ask teacher to enter their pass key/ password.
4. if the password is correct, it will take teache to new page.
5. this new page, will have multiple options for teacher:
   a) To create a session( Input: Session name, session time;  Ouput: session created).
      The session created by the teacher will expire after the alloted time by the teacher.
      The created session can be modified and deleted by the teacher.
   b) To upload the xslx file of students registration number.( stuents with these registration number will only be allowed to open the session of specific teacher).
   c) A teacher might take multiple classes, so teache can upload multiple xlsx file. And when session is created, teacher will have option to allow only students from only one of the uploaded xlsx file from mulitple xlsx files.
   d)After the session time is over, teacher will see the download option for the session, it will donwload the attendance of students.
   e)There will be a option for techer to rename the file name of xlsx file. By default file name will be current date and session name.
   f)Everytime new session is created by teacher, it will modify the same xlsx file by deleting all previous content and moifying it with new content.\

### NOTE:
1. Students can only login to the specific session , if the teacher has uploaded the xlsx file with the registration numbers of students.( so that no other students from other class can login for the session).
2. The passkey/password for the teacaher's account will be provided by the Admin, which can be modified upon teacher's request.
      
