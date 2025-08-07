# Pharmacy Management System

The Pharmacy Management System is a Java-based application designed to manage medicine inventory, customer purchases, and administrative tasks for a pharmacy. It provides separate interfaces for customers and administrators with various functionalities.

## Technologies Used

- **Java**: Core programming language for the application logic.
- **MySQL**: Database management system for storing medicine, customer, and admin data.
- **JDBC**: Java Database Connectivity for interacting with the MySQL database.
- **File I/O**: Used for generating bills in text format.
- **Object-Oriented Programming (OOP)**: Utilized for structuring the code with classes and methods.

## Features

### Customer Features
1. **Registration & Login**: Customers can register with personal details and log in using their credentials.
2. **Buy Medicine**: Purchase medicines from the available stock.
3. **Show Medicine**: View details of all available medicines (name, price, quantity, etc.).
4. **Remove Medicine**: Remove medicines from their purchase list.
5. **Request Medicine**: Request medicines that are not currently in stock.
6. **Make a Payment**: Generate a bill with the total amount, including GST.

### Admin Features
1. **Registration & Login**: Admins can register and log in to access administrative functions.
2. **Stock Check**: View the current stock of all medicines.
3. **Add New Medicine**: Add new medicines to the inventory with details like name, price, quantity, etc.
4. **Remove Medicine**: Remove medicines from the inventory.
5. **Update Quantity**: Update the quantity of existing medicines.
6. **Check Customer Requests**: View and process customer requests for medicines.

### Additional Features
- **Bill Generation**: Bills are saved as text files with details of purchased medicines and the total amount.
- **Input Validation**: Validates user inputs for mobile numbers, passwords, etc.
- **Database Integration**: All operations are synchronized with a MySQL database for persistent storage.

## Setup Instructions

1. **Prerequisites**:
   - Install Java Development Kit (JDK).
   - Install MySQL and set up the `pharmacy2` database.
   - Add the MySQL JDBC driver to your project.

2. **Database Setup**:
   - Create tables for `medicines`, `customer`, `admin`, and `request_list` as per the schema used in the code.

3. **Run the Application**:
   - Compile and run the `Pharmacy.java` file to start the application.

## Usage

1. **For Customers**:
   - Register or log in to access customer operations like buying medicines, viewing stock, or requesting medicines.

2. **For Admins**:
   - Register or log in to manage the medicine inventory, check stock, and process customer requests.
