## API Test Automation with Postman
This repository contains a collection of API tests implemented in Postman for the Simple Books API. The collection covers various scenarios, including creating clients, retrieving books, managing orders, and more. It also uses a Bearer Token to authenticate.

## Instructions for Running the Tests
1. Download both files, the collection and the environment
2. Open Postman.
3. Click on "Import" at the top left and import both files.
4. Select the environment in the Collection if necessary
5. Right click on the collection folder, and then click Run collection.

## Review Test Results:
Postman will display the test results in the "Tests" tab for each request.
Check the console for any additional information provided by the scripts.

## Additional Information
Each request includes pre-request scripts to set up necessary variables dynamically.
Test scripts include assertions to validate response status codes, body content, and other criteria.
The collection covers positive and negative scenarios for various API endpoints.
