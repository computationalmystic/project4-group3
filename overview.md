# Steps to Integration:

## 1. Build product road map and loose schedule for production, testing, and delivery

## 2. Define acception criteria for beginning stages of application

## 3. Verify accuracy of acception criteria with product owner

## 4. Plan out sprints for code creation based on priority and dependencies

## 5. Create simple introductory functionality
a. Create classes for user login profiles for teachers, students, TA's, and system admins
Classes: 'student', 'teacher', 'ta', 'sysAdmin'

b. Implement security checks to verify users after profile is created

c. Create empty page views with clear, consistent layout

d. Implement page flow redirection functionality based on what a user clicks/event listeners

e. Set up database to store user input
Student Table Values: 'id', 'classes', 'sectionEnrolled', 'name'
Teacher Table Values: 'id', 'classes', 'section', 'name'
TA Table Values: 'id', 'classes', 'section', 'name'
SysAdmin Table Values: 'id', 'name', 'clearance'

f. Create methods for accessing database values
Student Methods: login(), viewCourse(), viewAssignment(), submit(), upload(), addComment(), editProfile()
Teacher Methods: login(), viewCourse(), viewAssignment(), searchStudents(), editSection(), editTA(), editStudent(), editAssignment(), editGrade(), submitGrade(), addComment(), editProfile()
TA Methods: login(), viewCourse(), viewAssignment(), searchStudents(), submitGrade(), addComment(), editProfile()
SysAdmin Methods: viewCourse(), login(), searchStudents(), searchTeachers(), searchTA(), editStudent(), editTeacher(), editTA(), editCourse(), editProfile(), removeData()

g. Insert functionality to display mock data on pages created

## 6. Create system tests to test acception criteria

## 7. Move forward with next steps in rollout

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

We felt that the functions above were a good start in terms of implementing the system for a assignment submission service. We would continue forward by making sure the functions covered are a good base, then build the software through a divide and conquer approach where we have different indviduals working on different tasks that they are experts in. Along the way, we will have checkpoints to make sure work is being completed in a timely manner and we could allow developers to give quick progress reports/presentations on their work. 

