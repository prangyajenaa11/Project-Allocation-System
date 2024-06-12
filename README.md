# Project-Allocation-System
This repository contains a simple project allocation system for students at the Xavier School of Computer Science and Engineering. The system allows students to register their details, including their field of interest, and log in to the system.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Student Login**: Secure login for students using their roll number and password.
- **Project Registration**: Students can register their details and select their preferred fields of interest.
- **Responsive Design**: Adaptable UI for various screen sizes.
- **Modern Aesthetics**: Clean and modern design using CSS and external font libraries.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/project-allocation-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd project-allocation-system
   ```
3. Ensure you have a local server set up to serve the HTML files. You can use tools like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VSCode or a simple Python server:
   ```bash
   python3 -m http.server
   ```
4. Open `front.html` in your browser to access the login page.

## Usage
1. **Login Page**: Open `front.html` to see the login page. Enter your roll number and password to log in.
2. **Registration Page**: After logging in, you will be redirected to `index.html` where you can register your details and select your fields of interest.

## Files
- `front.html`: The login page for the system.
- `index.html`: The registration form for students to enter their details and project preferences.
- `style.css`: Stylesheet for `index.html`.
- `style1.css`: Stylesheet for `front.html`.
- `Styles_web.css`: Additional styles used across the project.

### Detailed File Description
1. **front.html**
   - Contains the login form for students.
   - Uses `style1.css` for styling.
   
2. **index.html**
   - Registration form for students.
   - Includes fields for name, roll number, date of birth, email, mobile number, semester, field of interest, and CGPA.
   - Styled with `style.css` and `Styles_web.css`.

3. **style.css**
   - Contains styles for `index.html`.
   - Uses the "Open Sans" font and sets up styles for the form and table elements.

4. **style1.css**
   - Contains styles for `front.html`.
   - Uses a gradient background and styles for the login box and form elements.

5. **Styles_web.css**
   - Additional styles used across the website.
   - Sets the background image for the body.
