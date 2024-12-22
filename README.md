# Express.js Route Handler Missing Error Handling for Invalid User IDs

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid or missing parameters.

## The Bug
The `bug.js` file contains a route handler that retrieves a user by ID.  It fails to handle cases where the `id` parameter is not a valid number, resulting in an unhandled exception.

## The Solution
The `bugSolution.js` file provides a corrected version of the route handler. It includes error handling to gracefully handle cases where the `id` parameter is invalid or the user is not found.