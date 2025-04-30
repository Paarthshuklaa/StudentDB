# Student Enrollment Form using JsonPowerDB

![Student Enrollment Form](https://i.imgur.com/placeholder-image.png)

## Table of Contents
1. [Description](#description)
2. [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
3. [Release History](#release-history)
4. [Illustrations](#illustrations)
5. [Scope of Functionalities](#scope-of-functionalities)
6. [Examples of Use](#examples-of-use)
7. [Project Status](#project-status)
8. [Sources](#sources)
9. [Other Information](#other-information)

## Description
This project is a web-based Student Enrollment Form that stores data in JsonPowerDB. It provides a simple and efficient way to manage student enrollment information with basic operations like Save, Update, and Reset. The form follows a specific workflow for data entry where fields are enabled/disabled based on the state of the primary key field.

The form is designed to store student data with the following fields:
- Roll No (Primary Key)
- Full Name
- Class
- Birth Date
- Address
- Enrollment Date

The application uses HTML, Bootstrap, JavaScript, jQuery, and JPDB CommonJS library to interact with JsonPowerDB.

## Benefits of using JsonPowerDB
1. **Schema-free**: JsonPowerDB is schema-free, allowing for flexible data modeling without predefined structures.
2. **High Performance**: It's built on PowerIndex technology, making it one of the fastest NoSQL databases.
3. **Real-time Database**: JsonPowerDB provides real-time database capabilities with minimal development and maintenance costs.
4. **Serverless Support**: Developers can use JsonPowerDB for serverless computing and development.
5. **Multi-mode Database**: It can be used as a document database, key-value database, and geospatial database.
6. **Simple to Use**: The JPDB API is very simple to use, requiring minimal coding effort for database operations.
7. **Nimble and In-Memory**: It's lightweight and in-memory, making it super-fast for operations.
8. **Cost Effective**: Reduces development and maintenance costs significantly.
9. **Web Services API**: Supports REST-style API access with HTTP.
10. **Built-in Security**: Provides multiple security layers for data protection.

## Release History
- **v0.1.0 (April 30, 2025)**: Initial release of the Student Enrollment Form with basic functionality.

## Illustrations
The project consists of a single web page with a form that has the following features:

1. **Initial State**: 
   - All fields except Roll No are disabled
   - Save and Update buttons are disabled
   - Reset button is enabled
   - Focus is set on Roll No field

2. **When Roll No is entered**:
   - If Roll No doesn't exist: All fields are enabled, Save button is enabled, focus moves to Name field
   - If Roll No exists: Data is loaded into the form, fields are enabled, Update button is enabled, Roll No field is disabled

3. **Form Validation**:
   - All fields are checked for empty values
   - Appropriate error messages are shown

4. **Control Buttons**:
   - Save: Stores new student data in JsonPowerDB
   - Update: Updates existing student record
   - Reset: Clears all fields and resets form to initial state

## Scope of Functionalities
The Student Enrollment Form provides the following functionalities:

1. **Data Entry**: Enter student details in a user-friendly form
2. **Data Validation**: Ensure all required fields are filled
3. **Data Storage**: Save student records to JsonPowerDB
4. **Data Retrieval**: Fetch existing student records by Roll No
5. **Data Modification**: Update existing student information
6. **Form Reset**: Clear all fields and start fresh

## Examples of Use
The form can be used in various educational contexts such as:

1. **School Admission Process**: Record new student enrollments
2. **Student Database Management**: Maintain up-to-date student records
3. **Course Registration**: Register students for specific classes or programs
4. **Academic Records**: Maintain basic student academic information

## Project Status
The project is in its initial release stage. Future enhancements may include:

- Adding search functionality to find students by name
- Implementing a student list view
- Adding pagination for multiple student records
- Implementing user authentication
- Adding data export capabilities

## Sources
1. [JsonPowerDB Documentation](http://login2explore.com/jpdb/docs.html)
2. [Bootstrap Documentation](https://getbootstrap.com/docs/3.4/)
3. [jQuery Documentation](https://api.jquery.com/)

## Other Information

### How to Use the Form
1. Enter a Roll No in the Roll No field and press Tab or click away
2. If the Roll No exists, the form will load existing data for editing
3. If the Roll No is new, fill in all the required fields
4. Click Save to store a new record or Update to modify an existing record
5. Click Reset to clear the form and start over

### Prerequisites
- Web Browser with JavaScript enabled
- Internet Connection to access CDN resources and JsonPowerDB API

### Setup and Installation
1. Clone this repository
2. Open index.html in your web browser
3. Replace the connection token in the JavaScript code with your own JsonPowerDB token
4. The form is ready to use

---

### JsonPowerDB Connection Details
- Base URL: http://api.login2explore.com:5577
- Database Name: SCHOOL-DB
- Relation Name: STUDENT-TABLE
- Connection Token: (Your connection token goes here)

---

*This project is developed as part of a programming assignment.*
