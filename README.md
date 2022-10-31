# Gradebook

## Synopsis
The subject of the project is a window application of the "grade book" type cooperating with the MySQL relational database. The project uses the JavaFX platform. The application is intended to be used on a maximum of a few positions in a small organization, e.g. a small school.

## Main features
* User registration and login
* Add, edit and delete students and grades
* Passwords are stored in the database in a hashed form
* The application allows you to export and import data as a backup to an XML file
* The data in the XML file is encrypted with the Jasypt library
* You can reset your password

## How to run a project?
1. Before starting the application, create a MySQL database called ___gradebook___ with user named __root__ with a blank password.

