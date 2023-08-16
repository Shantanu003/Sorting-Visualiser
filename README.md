# Quiz Application

## Introduction

QuizApp is a console-based application that offers a quiz management system for both students and teachers.

- In Teacher login
  
    - Teacher can create quizzes for studnets.
    - Teacher can view created quizzes by quiz name.
    - Teacher can view quiz history of particular quiz.

- In Student login

    - Student can attempt quiz assigned to him/her.
    - Student can view assigned quiz list.
    - Student can view history of attempted quizzes.
      
## Features 

- User Management
    - Users can log in using their credentials.
    - Password input is masked for security.
    - User types include students and teachers.

- Student Management
    - Students can log in and attempt assigned quizzes.
    - Students receive immediate feedback on their quiz attempts.
    - Quiz history is recorded and displayed, showing attempted quizzes, scores, and attempts left.

- Teacher Management
    - Teachers can log in and create quizzes.
    - Teachers can assign quizzes to students, with automatic assignment to all students.
    - Teachers can view quiz history, including student quiz attempts and scores.

- Quiz Creation
    - Teachers can create quizzes with specified names, questions, options, correct answers, explanations and maximum marks.
    - Quizzes are automatically assigned to all students upon creation.

- Quiz Attempt
    - Students can attempt assigned quizzes.
    - Students receive feedback on correct and incorrect answers.
    - Quiz scores and percentages are calculated and displayed.

## Modules 

- Login Module.

   - Teacher Login.
   - Student Login.
 
- Teacher Module.

  - Create Quiz.
  - View Created Quiz.
  - View Quiz History.

- Student Module.

  - Attempt Quiz.
  - View Assigned Quiz List.
  - View Quiz History. 

- LogOut Module.

## Environment Variables

The QuizApp utilizes the following environment variables:

  -  USER CLASS : Specifies the class for User.
  -  STUDENT CLASS : Specifies the class for Students.
  -  TEACHER CLASS : Specifies the class for Teachers.
  -  QUIZHISTORY CLASS : Specifies the class for QuizHistory.
  -  QUIZ CLASS : Specifies the class for Quiz.
  -  QUESTION CLASS : Secifies the class for Question.
  -  ANSWER CLASS : Specifies thw class for Answer.

 ## Validations
 
   -  Login Validation: Ensures valid username and password input during login.
   -  Quiz Assignment Validation: Checks for valid quiz assignment and availability.
   -  Quiz Attempt Validation: Validates student quiz attempts and available attempts.
   -  Input Validation: Verifies correct input format and range for various operations.

## Database
  QuizApp manages data using an in-memory database that includes:

  -  Global List of Users : Maintains user profiles with username, password, and role.
  -  Global List of Students : Maintains students profiles with studentName, enrollment number, etc.
  -  Student Quiz History : Records student quiz attempts, scores, and history.
  -  Teacher Quiz History Dictionary : Stores teacher-created quizzes and associated history.
 
