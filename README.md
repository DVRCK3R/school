# School Management Portal

A polished front-end school website and management portal built with HTML, CSS, and JavaScript. This project presents a fictional academic institution with a public homepage, student and teacher dashboards, registration and login flows, and multiple school administration pages.

## Description

School is a static web application designed to demonstrate how a modern school website could function for students, teachers, and administrators. The project includes sections for academic offerings, registration, attendance, fees, assignments, and schedule management. It focuses on user experience and client-side behavior without requiring a backend or database.

## Features

- Responsive landing page with hero banner and course highlights
- Student and teacher portal pages
- Registration and login interface
- Attendance tracking page
- Enrollment and fee information sections
- Assignment and grading pages
- Schedule and school information pages
- Dynamic front-end interactions powered by JavaScript
- Browser-based demo authentication using local storage

## Tech Stack

- HTML5
- CSS3
- JavaScript

## Project Structure

```text
school/
├── README.md
├── system/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── reg.html
│   ├── Student.html
│   ├── teacher.html
│   ├── Teacher.html
│   ├── Attendance.html
│   ├── enrollment.html
│   ├── fees.html
│   ├── schedule.html
│   ├── assignments.html
│   ├── grade-assignments.html
│   ├── style.css
│   ├── reg.css
│   ├── register.css
│   ├── student.css
│   ├── teacher.css
│   ├── script.js
│   ├── register.js
│   ├── auth.js
│   ├── att.js
│   ├── att.css
│   ├── city-sunset.jpg
│   ├── team.jpg
│   ├── book.jpg
│   └── other image assets
└── ...
```

## Getting Started

### Open directly in a browser

1. Clone the repository.
2. Open the `system` folder.
3. Launch `index.html` in your browser.

### Run locally with a web server

```bash
cd school/system
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Usage

- Visit the home page to explore the school website.
- Navigate to the registration and sign-in pages for the demo user flow.
- Review the student and teacher sections for portal-style content.
- Explore pages related to attendance, fees, assignments, and enrollment.

## Notes

This is a front-end demonstration project and does not include a real backend or database. User registration and authentication are simulated using browser storage (`localStorage` and `sessionStorage`) for demonstration purposes.

## License

This project is provided for educational and demonstration purposes.

## Acknowledgements

This project was created as a fictional school portal prototype for learning and frontend design practice.
