# Retired Hands Empowering System

A web application built to connect retired professionals with opportunities to contribute their skills — through volunteering, mentoring, or part-time engagements. Developed as an academic mini project during BSc Computer Science.

## Features

- User registration and login with session management
- District-based filtering to find local opportunities
- Dynamic form handling with validation
- CRUD operations for managing user profiles
- Responsive UI built with Bootstrap

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, Bootstrap, JavaScript |
| Backend | PHP |
| Database | MySQL |

## Project Structure

```
├── index.php               # Landing page
├── login.php               # User login
├── logout.php              # Session logout
├── reg.php / reg1.php / reg3.php  # Multi-step registration
├── menu.php                # Navigation menu
├── load_districtindex.php  # Dynamic district loading
├── connection.php          # DB connection
```

## How to Run Locally

1. Install [XAMPP](https://www.apachefriends.org/) or any PHP + MySQL stack
2. Clone this repository into the `htdocs` folder
3. Import the database SQL file into phpMyAdmin
4. Visit `http://localhost/retired-hands-empowering-system` in your browser

## Project Type

Academic Mini Project — BSc Computer Science
