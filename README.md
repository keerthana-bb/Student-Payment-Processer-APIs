# Student API Collection

This repository contains a collection of API endpoints related to student data management.

## Description

The Student API Collection provides various endpoints for retrieving and managing student-related data within a campus management system. It includes endpoints for retrieving payment processor accounts, ACH payment processor accounts, ACH detail data changes, payment processors, and specific payment processors by ID.

## Getting Started

To use the API endpoints, follow these steps:

1. Clone or download this repository to your local machine.
2. Import the provided Postman collection (`Student_API_Collection.json`) into your Postman application.
3. Configure the necessary environment variables such as `username` and `password` for authentication.
4. Start making requests to the desired endpoints.

## Available Endpoints

- **Retrieve Payment Processor Accounts**: `GET /ds/campusnexus/PaymentProcessorAccounts`
- **Retrieve ACH Payment Processor Accounts**: `GET /ds/campusnexus/PaymentProcessorAchAccounts`
- **Retrieve ACH Detail Data Changes**: `GET /ds/campusnexus/PaymentProcessorAchDetailDataChanges`
- **Retrieve Payment Processors**: `GET /ds/campusnexus/PaymentProcessors`
- **Retrieve Specific Payment Processor by ID**: `GET /ds/campusnexus/PaymentProcessors/{id}`

## Authentication

All endpoints require basic authentication. Provide your username and password as query parameters in the request URL.

## Contributions

Contributions to this API collection are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or create a pull request.

## License

This API collection is released under the [MIT License](LICENSE).
