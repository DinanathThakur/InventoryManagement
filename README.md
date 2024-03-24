# Inventory Management

## Technologies Used
1. HTML
2. CSS
3. JavaScript
4. PHP
5. MySQL 5.7
6. jQuery library
7. Bootstrap
8. DataTables

## File Structure
### index.html
- Contains frontend related codes, including tables and forms.

### app.php
- Main entry point for PHP development.
- Defines all required classes:
    - **Database**: Main class for database connectivity.
    - **Request**: Handles request-related transactions.
    - **Item**: Handles item-related transactions.
    - **Summary**: Handles summary-related transactions.
    - **App**: Main class to handle requests (acting as an API controller), managing features such as creating new requests, listing all requests with items and item types, editing requests, and deleting requests.

### script.js
- Contains all scripts required for the app.
- Implements a main class to handle all functionalities.

### style.css
- Contains styles required for the app.

## Features

- **Add New Request**: Users can add a new request by filling out required details in a Bootstrap modal.
- **View All Requests**: Displays all requests using the DataTables library.
- **Edit Request**: Users can edit a request by clicking on the gear icon, selecting the edit option, and updating items in a pre-filled form.
- **Delete Request**: Users can delete a request by clicking on the gear icon, selecting the delete option, and confirming deletion in a prompt.
- **Order Requests**: Orders requests by inserting consolidated order records into the summary table.
