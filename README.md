# Buildathon_6_T3-T4
Gym Membership Management System and Student Result Publisher application using Java SpringBoot
## Student Result Publisher API

### Overview

This API enables the management of student results, including storing student details, calculating grades, and retrieving student records.

### Features

Add a new student with personal details and subject-wise marks

Calculate grades based on marks and update the records

Retrieve details of all students

Student Fields

Name

Roll Number

Department

Marks obtained in 6 subjects:

Subject Name

Marks Obtained

Maximum Marks

Grades (Based on provided grading chart)

Qualification Status (Passed/Failed)

API Endpoints

/studentEntry - Add a new student

/calculateGrades - Compute and update student grades

/getAllStudents - Retrieve all student records

## Gym Membership Management System API

### Overview

This API helps gym administrators manage memberships efficiently, tracking active members and their workout plans.

### Features

Register a new gym member with essential details

Retrieve all active members

Member Fields

Member ID (Not system-generated, must be unique)

Name (Full name of the gym member)

Membership Type (Monthly or Annual)

Active Status (Indicates if the membership is currently active)

Workout Plan (e.g., Strength, Cardio, Yoga)

API Endpoints

/registerMember - Add a new gym member

/getActiveMembers - Retrieve all active gym members
