# Test Project: Manual API Testing with Postman

This project showcases manual REST API testing skills using Postman. The public PokéAPI was used as the testing target.

## 🗂️ Collection Overview

This Postman collection contains basic smoke tests for the PokéAPI endpoints.

### Test Scenarios Covered:
1.  **Positive GET Request:** Verifies fetching data for a specific, existing resource (the Pokémon `pikachu`). Expected Result: `200 OK` status.
2.  **Negative GET Request:** Checks the error handling for a non-existent resource. Expected Result: `404 Not Found` status.
3.  **GET Request with Query Parameters:** Validates the use of query parameters to limit the results (retrieving a list of 5 Pokémon). Expected Result: `200 OK` status.

## 🛠️ How to Use

1.  Download the `.json` collection file from this repository.
2.  Open the Postman application.
3.  Click the "Import" button and select the downloaded file.
4.  Once imported, the collection will be available to run the tests.
