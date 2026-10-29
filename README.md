# System description

A simple school website and management portal built with HTML, CSS, and JavaScript. The project includes a public landing page, student dashboard views, teacher access pages, registration/login flows, and several school management modules such as attendance, enrollment, fees, and assignments.

## Overview

This repository contains a front-end school system that showcases a modern academic website and allows users to browse the institution, sign up, log in, and view school-related information. The app is designed as a static web project and uses browser storage (`localStorage` / `sessionStorage`) for simple authentication and user management.

## Features

- School landing page with hero section and course listings
- Student interface and student-related information pages
- Teacher login and teacher dashboard pages
- Registration and sign-in pages
- Attendance tracking page
- Enrollment and fee information pages
- Assignment and grading views
- Responsive styling with CSS
- JavaScript-powered client-side interactions

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
│   └── images and assets (.jpg files)
└── ...
```

## Getting Started

1. Clone the repository.
2. Open the `system` folder.
3. Launch `index.html` in your browser.

You can also run it using a simple local web server if you prefer:

```bash
cd school/system
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Technologies Used

- HTML
- CSS
- JavaScript

## Notes

This project is a frontend demonstration and does not include a backend or database. User data is stored in the browser using client-side storage for demo purposes.

## License

This project is provided as-is for educational and demonstration purposes.
