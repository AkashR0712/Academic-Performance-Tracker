# Academic-Performance-Tracker

The Academic-Performance-Tracker is a web application designed to manage and track academic performance efficiently. Built using HTML, CSS, JavaScript, and Node.js, it leverages the MVC (Model-View-Controller) architecture to separate concerns and enhance maintainability. The application supports two types of users: students and teachers, each with distinct functionalities accessible through a user-friendly interface.

## Features

### User Authentication

- **Students**: Students can log in by entering their roll number and date of birth to view their individual results.
- **Teachers**: Teachers can log in to view, add, edit, and delete student records.

### Student Dashboard

- Students can see a detailed view of their academic results, including grades for each subject.

### Teacher Dashboard

- Teachers have access to a comprehensive list of all student records.
- Teachers can perform CRUD (Create, Read, Update, Delete) operations on student records, allowing for efficient result management.

## Technology Stack

### Frontend

- **HTML**: For structuring the web pages.
- **CSS**: For styling the web pages.
- **JavaScript**: For client-side scripting to enhance interactivity.

### Backend

- **Node.js**: For server-side scripting.
- **Express**: As the web application Middle-ware framework.
- **MongoDB**: As the database for storing user and result data.
- **Mongoose**: For object data modeling (ODM) with MongoDB.
- **EJS (Embedded JavaScript)**: For rendering dynamic content on the web pages.

## Architecture

### Model-View-Controller (MVC)

- **Model**: Represents the data structure (e.g., student and teacher schemas).
- **View**: Represents the UI components (e.g., HTML and EJS templates).
- **Controller**: Handles the logic and user input, interacts with the Model, and renders the appropriate View.


