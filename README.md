# Express.js - Missing Property in Request Body
This repository demonstrates a common error in Express.js applications where an unhandled error occurs when a request body is missing an expected property.  The bug occurs when attempting to access a property on `req.body` that isn't present in the incoming request, leading to an uncaught exception.

## Bug
The `bug.js` file contains the problematic code, which fails to handle cases where the request body does not contain a 'name' property.

## Solution
The `bugSolution.js` file provides a corrected version, implementing proper error handling to gracefully manage situations where expected properties are missing from the request body.

This example showcases the importance of robust error handling in Express.js applications to prevent crashes due to unexpected or malformed requests.