# Unhandled Request Issue in Node.js HTTP Server

This repository demonstrates a common, yet subtle, error in Node.js HTTP servers where requests are not handled correctly.  The server starts without errors, but fails to respond to client requests.

## Bug

The `bug.js` file contains the problematic code. The server listens on port 8080, but it might not respond correctly to requests. 

## Solution

The `bugSolution.js` file provides a corrected version of the code.