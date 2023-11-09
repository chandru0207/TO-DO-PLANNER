       
## 1. Introduction
### 1.1 Purpose
The purpose of this document is to specify the requirements and functionality of the Task Planner application.

### 1.2 Scope
The Task Planner application is a web-based task management system that allows users to create, manage, and track their tasks and to-do lists. It is built using HTML, CSS, Java Spring Boot, and React.js.

### 1.3 Definitions, Acronyms, and Abbreviations
- SRS: Software Requirements Specification
- HTML: HyperText Markup Language
- CSS: Cascading Style Sheets
- Java: The programming language used in the backend (Java Spring Boot)
- React.js: The JavaScript library used for the frontend

## 2. System Overview
### 2.1 System Description
The Task Planner application will provide users with the ability to:
- Create user accounts
- Log in and log out
- Create, update, and delete tasks
- Organize tasks into categories or projects
- Set due dates and priorities for tasks
- View and filter tasks based on various criteria
- Receive notifications and reminders for upcoming tasks
- Collaborate with other users on shared tasks

### 2.2 System Architecture
The Task Planner application will follow a client-server architecture. The frontend will be developed using React.js, while the backend will be developed using Java Spring Boot.

## 3. Functional Requirements
### 3.1 User Registration and Authentication
- Users can create accounts with unique usernames and passwords.
- Users can log in and log out of the application.
- Authentication will be implemented to ensure data security.

### 3.2 Task Management
- Users can create, update, and delete tasks.
- Tasks can have a title, description, due date, priority, and category.
- Tasks can be organized into categories or projects.
- Users can mark tasks as completed.
- Users can filter tasks based on due date, priority, and category.

### 3.3 Notifications and Reminders
- Users will receive notifications and reminders for upcoming tasks.
- Users can choose notification preferences, such as email or in-app notifications.

### 3.4 Collaboration
- Users can invite other users to collaborate on shared tasks.
- Collaborators can view and update shared tasks.

## 4. Non-Functional Requirements
### 4.1 Performance
- The system should respond to user actions promptly.
- The application should be scalable to handle a large number of users and tasks.

### 4.2 Security
- User data, including passwords, should be securely stored and transmitted.
- User authentication and authorization mechanisms should be robust.

### 4.3 Usability
- The user interface should be intuitive and user-friendly.
- The application should be responsive and accessible on various devices.

### 4.4 Compatibility
- The application should be compatible with popular web browsers.
- The backend should be compatible with different operating systems.

## 5. User Interface Design
- The user interface will be designed using HTML and CSS, providing an attractive and user-friendly experience.

## 6. Testing
- Thorough testing, including unit testing and integration testing, will be performed to ensure the application's reliability and stability.

## 7. Deployment
- The application will be deployed on a web server for public access.

## 8. Maintenance and Support
- Ongoing maintenance and support will be provided to address issues, add new features, and ensure the application's continued functionality.

## 9. Conclusion
This Software Requirements Specification (SRS) outlines the requirements and functionality of the Task Planner application, a web-based task management system. It serves as a foundation for the development, testing, and deployment of the application.




# React To-Do List

This is a simple To-Do list app done with React. All tasks are saved into browser's local storage only. The app development
was inspired by the first brazilian live coding of the [React Nanodegree Program](https://udacity.com/course/react-nanodegree--nd019). 

<img src="https://raw.githubusercontent.com/computationalcore/react-to-do-list/gh-pages/to-do-list.gif" alt="Todo List" style="width: 320px; height: 582px"/>

## Demo

[computationalcore.github.io/react-to-do-list](https://computationalcore.github.io/react-to-do-list)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing 
purposes. 

### Prerequisites

The project can be built with npm or yarn, so choose one of the approach bellow in case you don't 
have any installed on your system. 

* npm is distributed with Node.js which means that when you download Node.js, 
you automatically get npm installed on your computer. [Download Node.js](https://nodejs.org/en/download/)

or

* Yarn is a package manager built by Facebook Team and seems to be faster than npm in general.  [Download Yarn](https://yarnpkg.com/en/docs/install)

### Installing

To download the project follow the instructions bellow

```
git clone https://github.com/computationalcore/react-to-do-list
cd myreads
```

Install dependencies and run with:
 
npm
```
npm install
npm start
```
or

yarn
```
yarn install
yarn start
```

## Versions

v1.0 
* Default project implementation 
 
v1.1 
* Change to material UI based interface
* Task transitions animations
* Remove tasks capabilities

## Authors
Vin Busquet
* [https://github.com/computationalcore](https://github.com/computationalcore)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details


## Acknowledgments
* [Udacity](https://www.udacity.com/)
* [Matheus Marsiglio](https://github.com/mtmr0x)
* [Thales Moreira Carvalho](https://github.com/thalescomp)
