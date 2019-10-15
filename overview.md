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



