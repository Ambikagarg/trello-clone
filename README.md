

=> Update List Endpoint: This API endpoint would enable users to update the name of an existing list. It would require the list ID and the new list name as input parameters and would update the corresponding row in the lists table.

=> A new table would need to be created to store comments made by users on tasks. 

=> For error handling in the API endpoints, the following approaches can be used:

a. Input Validation: Validate the input parameters to ensure they meet the required criteria. Check if the provided board ID, list ID, or task ID exists and if the names or text are not empty.

b. Error Responses: Return appropriate error responses with meaningful messages and corresponding HTTP status codes when encountering errors. For example, return a 404 Not Found if a requested resource doesn't exist or a 400 Bad Request if the input parameters are invalid.

c. Exception Handling: Catch and handle exceptions that may occur during the execution of the API endpoints. Handle database errors, input validation errors, or any other unexpected errors gracefully. Log the error details for debugging purposes.

d. Consistent Error Format: Define a consistent error format for the API responses. Include an error code, a descriptive message, and optionally additional details. This helps clients parse and handle errors consistently.
