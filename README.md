# Registration Form Project

This is a simple registration form built using React, Formik for form handling, Yup for validation, and styled-components for styling the form. The form includes input fields for name, email, password, and confirm password, with real-time validation and submission handling.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Folder Structure](#folder-structure)
- [Validation Rules](#validation-rules)
- [Contributing](#contributing)
- [License](#license)

## Demo

A live demo of the project can be accessed [here](#).

## Features

- Real-time form validation using **Formik** and **Yup**
- Password strength validation (uppercase, lowercase, number, and special character)
- Styled with **Styled Components**
- Responsive design using media queries
- Error handling and error message display
- Form reset on successful submission

## Technologies Used

- **React**: Frontend JavaScript library for building user interfaces.
- **Formik**: Handles form state, validation, and submission.
- **Yup**: Schema-based validation for form inputs.
- **Styled Components**: Styling components with tagged template literals.
- **Unsplash API**: Used for the background image.

## Getting Started

To get a local copy of this project up and running, follow the steps below.

### Prerequisites

- Node.js installed on your machine.
- A code editor like VS Code.

### Installation

1. **Clone the repo:**

   ```bash
   git clone https://github.com/yourusername/registration-form.git

2. **Navigate to the project folder:**

   ```bash
   cd registration-form


3. **Install dependencies:**

   ```bash
  npm install


4. **Start the development server:**

   ```bash
   npm start

### Folder Structure

├── public
├── src
│   ├── App.js                # Root component
│   ├── index.js              # Entry point for the app
│   ├── Registration.js       # Registration form component
│   ├── Styles
│   │   └── globalStyles.js   # Global styles with styled-components
│   ├── schemas
│   │   └── index.js          # Form validation schema with Yup
├── README.md                 # Project documentation
├── package.json              # Project metadata and dependencies
└── .gitignore                # Files and directories to ignore in Git

