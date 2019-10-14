# Classes to be created
1. Student
2. Teaching Assistant (TA)
3. Instructor
4. System Administrator
# Variables for each class
## Student
-Pawprint\
-Name
## Teaching Assistant
-TA ID\
-Name
## Instructor
-Instructor ID\
-Name
## System Administrator
-Admin ID\
-Name
# Functions for each class
## Student
1. Login/Logout
2. View Assignments
3. Upload Assignments
4. Provide comments to notify TA of any problems
## Teaching Assistant
1. Login/Logout
2. View assignments
3. View courses they are assigned to
4. Search students in a course
5. Download student submissions
## Instructor
1. Login/Logout
2. Create/Edit/Remove courses
3. Same functions for TAs, students, assignments for respective class
## System Administrator
1. Add/edit/remove instructors

# Functions: 
## Upload/Reupload files
	File Storage, Server Configuration, Database file-tracking system, Web User Interface,
	Web Server, classes for managing logic
	Student Class: name, id, assignment
## Login/Logout
	Database tracking who can/cannot login/Web UI and Server, classes for logic, network
	security for unwanted users
	All classes will be used for login
	Name, id, and password are needed to login
## Comment on Assignment
	Implement UI that allows user to text and show up on screen, server for web, machine
	learning to track comments
	Student, TA should be allowed to comment on assignment pages
## Adding/Removing courses, sections, students
	Database to keep track of changes made, web UI and server, user authentication to make
	sure that the changes made are from an appropriate user 

For uploading/reuploading files, we need to have the above mentioned software implementation in order to be able to build the proper infrastructure. Logging in and out requires similar software implementation as well as network security to make sure that users that should not have access to the system do not gain access in any circumstance. With the commenting functionality, we need to implement a UI that enables users to be able to see comments and reply. A machine learning tool can also be implemented to track the use of inappropriate language on any comments. When adding/removing something in the system, we will need a database tracking the queries made to add and remove different inputs, an appropriate UI and server, as well as user authentication to make sure the changes are made by a user in the system.
