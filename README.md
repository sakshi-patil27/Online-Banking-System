# Online-Banking-API 

This repository contains the RESTful API for an online banking application developed using Spring Boot. The API includes features for user authentication, account management, and various banking transactions, ensuring a secure and efficient experience for users.

## Features

 1) User Registration and Authentication
  - APIs for customer and admin registration.
  - Login API for both user types.
  - Ability to update user details.

 2) Account Management
  - Fetch user and admin information by ID or account number.
  - API for generating a random account number based on specific conditions.

 3) Transaction Management
  - APIs for performing transactions such as:
    - Deposit and withdrawal.
    - Fund transfers between accounts.
  - Fetch transaction history based on date ranges or account number.

 4) Checkbook Requests
  - Customers can request checkbooks.
  - Admins can view and manage checkbook requests.
  
 5)  Security
  - JWT-Based Authentication
     - Implemented JSON Web Tokens for secure user authentication.
     - Role-based access control to manage permissions.

## Documentation
  API Documentation
     - Swagger integrated for interactive API documentation and testing.

## Validation

  - All data is validated before being added to the database to ensure data integrity.

## Testing

  - All APIs have been tested using Postman to ensure proper functionality and performance.

## Project Zip

 You can download the complete project ZIP file.

## Getting Started

To get started with the API:

1. Clone the repository.
2. Set up your environment with the required dependencies.
3. Run the application.
4. Use Swagger or Postman to test the endpoints.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.


Feel free to modify any section according to your project's specific details or requirements! Don't forget to replace `link-to-your-zip-file` with the actual link to the ZIP file.
