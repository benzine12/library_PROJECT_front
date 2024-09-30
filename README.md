# Book CRM

Book CRM is a web-based application designed to manage books, customers, loans, and reports. The app is built using HTML, Bootstrap, and JavaScript, and it uses Axios to communicate with the backend API. This project aims to provide an easy-to-use interface for managing a book collection, customer database, and loan history.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)

## Features

- **Book Management:** View and manage a collection of books. Add new books, update book information, and toggle their availability status.
- **Customer Management:** Keep track of customer information, including personal details, loan activity, and account status.
- **Loan Management:** Manage loans, including issuing and returning books, and calculating time remaining or overdue.
- **Reports and Analytics:** Generate reports on the status of books, loans, and customers. Visualize data through charts and graphs.
- **Search:** Search across books and customers with real-time suggestions.
- **Responsive Design:** Fully responsive UI for mobile and desktop.

## Technologies

- **Frontend:**
  - HTML5
  - CSS3 (with Bootstrap 5 for styling)
  - JavaScript (with Axios for HTTP requests)
  - Font Awesome icons
  - Chart.js for data visualization

- **Backend:** The app is integrated with a Flask-based API (not included in this repository). Axios is used to interact with the backend endpoints for fetching and modifying data.

## Project Structure

```plaintext
📁 css/
   └── styles.css           # Custom CSS for additional styling
📁 js/
   └── main.js              # JavaScript logic for client-side interactions (fetching data, handling modals)
📁 img/
   └── (images used in the project)
📄 index.html               # Main dashboard (homepage)
📄 books.html               # Book management view
📄 customers.html           # Customer management view
📄 loans.html               # Loan management view
📄 reports.html             # Reports view with charts
📄 README.md                # Project documentation
