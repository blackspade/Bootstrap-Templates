# Bootstrap 5.3 Projects

This repository contains three projects built using **Bootstrap 5.3**, **jQuery**, and **Font Awesome**:
1. **Collapsible Cards**: A dynamic card layout with collapsible sections.
2. **Ledger**: A table-based ledger with CRUD functionality and CSV export.
3. **Job Application**: An online job application form with validation and modal agreement.

## Features

### 1. Collapsible Cards
- **Dynamic Collapse**: Cards can be expanded or collapsed by clicking the header.
- **Header Color Change**: Card headers turn **blue** when open and **black** when closed.
- **Font Awesome Icons**: Caret icons (`fa-caret-up` and `fa-caret-down`) indicate the collapse state.

### 2. Ledger
- **CRUD Operations**: Add, delete, and edit rows in the ledger table.
- **CSV Export**: Export the ledger data as a CSV file.
- **Total Calculation**: Calculate the total dollar amount of all transactions.
- **Predefined Data**: Fill the table with sample data for testing.

### 3. Job Application
- **Form Validation**: Validate user input for required fields and formats (e.g., phone number, zip code).
- **Modal Agreement**: Users must agree to terms before submitting the form.
- **Dynamic Form Submission**: Log form data to the console (can be extended to submit to a backend).

## Technologies Used

- **Bootstrap 5.3**: For styling and responsive design.
- **jQuery**: For dynamic behavior and DOM manipulation.
- **Font Awesome**: For icons used in buttons and headers.

---

## Getting Started

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge).
- Basic knowledge of HTML, CSS, and JavaScript.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/blackspade/Bootstrap-Templates.git
   cd Bootstrap-Templates
   ```

2. **Open the Projects**:
   - Open the following files in your browser:
     - `Collapseable-Card.html` for the collapsible cards.
     - `ledger.html` for the ledger application.
     - `application.html` for the job application form.

---

## Project Details

### 1. Collapsible Cards (`Collapseable-Card.html`)
- **Usage**:
  - Click on any card header to expand or collapse the card.
  - Observe the header color change and the caret icon toggle.
- **Customization**:
  - Add more cards by copying the existing card structure and updating the `id` attributes.

### 2. Ledger (`ledger.html`)
- **Features**:
  - **Add Row**: Add a new row to the ledger table.
  - **Delete Row**: Delete the last row from the table.
  - **Fill Table**: Populate the table with predefined sample data.
  - **Calculate Total**: Calculate and display the total dollar amount.
  - **Export CSV**: Export the table data as a CSV file.
- **Customization**:
  - Modify the predefined data in the `data` array to suit your needs.

### 3. Job Application (`application.html`)
- **Features**:
  - **Form Validation**: Ensures all required fields are filled out correctly.
  - **Modal Agreement**: Users must agree to terms before proceeding.
  - **Dynamic Submission**: Logs form data to the console (can be extended for backend submission).
- **Customization**:
  - Add or remove form fields as needed.
  - Modify the validation rules in the JavaScript section.

---

## Code Structure

### Files
- **`Collapseable-Card.html`**: Collapsible cards with dynamic header colors.
- **`ledger.html`**: Ledger table with CRUD operations and CSV export.
- **`application.html`**: Job application form with validation and modal agreement.

### Dependencies
- **Bootstrap 5.3**: Linked via CDN in the `<head>` section.
- **jQuery**: Linked via CDN at the end of the `<body>` section.
- **Font Awesome**: Linked via CDN in the `<head>` section.

---

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

1. Fork the repository.
2. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [Bootstrap](https://getbootstrap.com/) for the responsive design framework.
- [jQuery](https://jquery.com/) for simplifying JavaScript functionality.
- [Font Awesome](https://fontawesome.com/) for the icons.
