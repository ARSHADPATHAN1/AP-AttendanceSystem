# AP-AttendanceSystem
In this Attendance System the Attendance for students is marked using Face verification. Create account by registering as a user faculty and Login to account. After Login the faculty has the access to add a students, take Attendance, modify Student details. The faculty can search Attendance of a student using Multiparameter Search, by specifying the student ID, date of attendance, period of Attendance.

The credentials for the Faculty are provided by superuser who has access to the whole database. Alse we can create faculty as a user through register signup and then login to the main account.

In this system you can register as a user faculty through signup and using social account google or facebook. Through google and facebook social account, this web app only creates user, The credentials for the Faculty are provided by the superuser who has access to the whole database. Only the superuser can create faculty .

We can add multiple faculty in user through superuser.

Django web framework is used for the development of the whole web app. OpenCv and face_recognition API's were used for the development of Face Recognizzer. The Face Recognizer can detect multiple face at a time and mark their attendance into Database.

Note: When we start taking attendance through the portal, sometime it might be taking time due to Opencv and Face recognition.

Note: Python version 3.9.13 is use for this project. And dlib package required for installation of face_recognition api is also uploaded.
