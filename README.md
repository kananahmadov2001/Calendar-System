<div align="center">
    <h1 id="Header">Calendar-System</h1>
</div>

## Overview
The Calendar-System is a web application that allows users to manage and share events efficiently. Users can log in, create and manage events, and interact with features like tagging, searching, and sharing calendars. The project includes robust security features such as CSRF token authentication, input validation, and protection against SQL injection and XSS attacks.

```
Note: This was my lab 5 project for my Rapid Prototype Dev. class I took at WashU with a team of 2.
```

## Project Link
- **Homepage**: [Calendar System Homepage](http://ec2-50-17-104-237.compute-1.amazonaws.com/~kananAhmadov/module-5-group/home.php)

## Login Details
Use one of the following credentials to log in:
| Username  | Password      |
|-----------|---------------|
| abc       | `3tc!`        |
| red       | `red`         |
| kanan     | `kanan,2001`  |

Alternatively, you can create a new user by entering a username and password on the homepage and clicking **Register**.

## Technologies/Tools Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Asynchronous Communication**: Fetch API for AJAX requests
- **Frameworks/Libraries**: Bootstrap Icons for styling

## Features

- **User Management**:
  - Login and Registration: Users can log in using predefined credentials or create a new account.
  - Session Security: CSRF token authentication and secure sessions ensure user data is protected.

- **Event Management**:
  - Add, edit, and delete events dynamically.
  - Tag events with specific categories for easy filtering.
  - Search events by category, date, or tag.

- **Tag Feature**:
  - Users can categorize events by tags and enable/disable these tags in the calendar view for better organization.

- **Search Feature**:
  - A search bar allows users to filter events by category, date, or tag.

- **Share Feature**:
  - Users can share their calendar with additional users, enabling collaboration.

## Security
- Input validation to prevent SQL injection and XSS attacks.
- CSRF token implementation for enhanced session security.
- JSON-based responses for secure and structured server communication.
