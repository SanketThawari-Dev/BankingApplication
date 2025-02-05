# Banking Application

## Overview

This Banking Application is designed to manage essential banking operations, including account creation, deposits, withdrawals, and transaction history management. 
It provides a user-friendly interface for both bank managers and customers to perform their respective tasks efficiently.


## Features

- **Bank Manager Operations**:
  - Add new customers by entering their first name, last name, etc.
  - Open accounts for existing customers with a selection of currency types.
  - View and manage the list of all customers.

- **Customer Operations**:
  - Log in using their name and account number.
  - Deposit funds into their account.
  - Withdraw funds from their account.
  - View transaction history with date filters.

## Technologies Used

- Java
- JDBC
- Servlet
- JSP
- MySQL
- HTML
- CSS
- Bootstrap

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Maven
- MySQL Server

### Installation :-

1. Clone the repository**:
   
       git clone https://github.com/SanketThawari-Dev/BankingApplication.git

2. Navigate to the project directory:
   
       cd BankingApplication
   
3. Configure the database:
   
   * Create a MySQL database named banking_app.
   * Update the database configuration in src/main/resources/application.properties with your MySQL username and password.
  
4. Build the project:

       mvn clean install
   
5. Run the application:

       mvn run
   
6. Access the application: Open your browser and navigate to http://localhost:8080.

## Usage

### Bank Manager:
  * Log in using manager credentials.
  * Add new customers and open accounts for them.
  * View and manage existing customers.
    
### Customer:
  * Log in using their name and account number.
  * Deposit or withdraw funds.
  * View their transaction history.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

