# React CRUD Application

This project is a React-based CRUD (Create, Read, Update, Delete) application developed as part of the "Architecture des composants" module practical work (TP). It interfaces with a backend REST API to manage customer data.

## Features

- **List Customers**: View a table of all existing customers.
- **Create Customer**: Add a new customer via a form.
- **Update Customer**: Edit existing customer details.
- **Delete Customer**: Remove a customer record.

## Technologies Used

- **React**: Frontend library for building the user interface.
- **Axios**: Promise based HTTP client for the browser and node.js.
- **Bootstrap**: CSS framework for styling and responsive design.

## Prerequisites

Before running this application, ensure you have the following:

- **Node.js**: Installed on your machine (v14+ recommended).
- **Backend Service**: A REST API running on `http://localhost:8080/api/rest/customer` handling the customer data operations.

## Installation

1. Navigate to the project directory:

    ```bash
    cd tp1
    ```

2. Install the necessary dependencies:

    ```bash
    npm install
    ```

## Running the Application

In the project directory, you can run:

```bash
npm start
```

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## Project Structure

- `src/api/axiosConfig.js`: Axios instance configuration with base URL.
- `src/components/CustomerList.jsx`: Component to display the list of customers.
- `src/components/CustomerComponent.jsx`: Component to handle form inputs and CRUD operations.
- `src/App.js`: Main component that orchestrates state and renders the application.


