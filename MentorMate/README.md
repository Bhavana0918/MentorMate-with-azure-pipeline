# CH_2023_Java_Team2
# MentorMate Documentation

## Overview
MentorMate is a platform that connects mentors and mentees to track progress, provide feedback, Objectives and Key-Results, as well as personalized guidance.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
  - [User Authentication](#user-authentication)
  - [User Registration](#user-registration)
  - [Mentor Dashboard](#mentor-dashboard)
  - [Mentee Dashboard](#mentee-dashboard)
  - [Email Notifications](#email-notifications)

## Features
- User Registration: Facilitates account creation for users, requiring name, email, and password.
- Role-Based Login: Automatically directs users to the appropriate dashboard (mentor or mentee) based on their designated role.
- Mentee Performance Rating: Implements a system for assigning ratings to mentees based on their demonstrated performance.
- Mentor Dashboard:
    - Displays a comprehensive list of mentees assigned to the mentor, along with their respective Objectives and Key Results (OKRs).
    - Enables mentors to rate mentees against each task.
    - Facilitates the addition of objectives and key results for mentees.
    - Offers functionality for adding comments and providing feedback.
    - Triggers email notifications to mentees upon the addition of objectives, key results, comments, or ratings.
- Mentee Dashboard:
    - Presents a clear overview of the mentee's OKRs, along with comments and ratings provided by their mentor.
    - Offers information regarding other mentees within the same mentor group, including their respective ratings.

## Technology Stack
- Database: MySQL
- Frontend: HTML+Thymeleaf, CSS, JavaScript
- Backend: Hibernate, Spring Boot

## Installation
1. Clone the repository: git clone https://github.com/IN-Valtech/CH_2023_Java_Team2.git
2. Set up the MySQL database and configure the connection in the application.
3. Navigate to the project directory and run the application: mvn clean spring-boot:run
4. Access the application at [http://localhost:8080](http://localhost:8080)

## Usage
### User Authentication
- Use your email and password to register and log in.
- Based on the role mapped in the database, you will be directed to the mentor or mentee dashboard.
### Sample Data
- Mentor: email: richasharmaa.21.20@gmail.com
- Mentee: email: chandana.n47@gmail.com
- Admin: email:  notpoojitha@gmail.com
- Password - Abcd@123

### User Registration
- Provide your name, email, password, designation and select your role.

### Mentor Dashboard
- View all mentees assigned under logged in mentor.
- Select the mentee to view their information and all the Objectives and key-results assigned to them.
- Add new Objectives and Key-results to a mentee.
- Add a comments against each key-result to provide feedback to the mentee.
- Rate performance of mentee against each key-result.
- View overall rating of the mentee to evaluate mentee performance.

### Mentee Dashboard
- View all Objectives and Key-Results assigned to logged in mentee by their mentor.
- View mentor feedback comments against each key-result.
- View the rating assigned by mentor evaluating mentee's performance.
- Access overall performance rating based on mentee's demonstrated performance.

## Email Notifications
- Receive Email notification on registering to the platform.
- Mentee will receive an email notification about all updates whenever their mentor adds a new Objective and Key-result, Comment, or Rating.

Note: This documentation serves as a guide for the MentorMate platform. For any inquiries or issues, please refer to the [GitHub repository](https://github.com/IN-Valtech/CH_2023_Java_Team2) or contact the project team.
