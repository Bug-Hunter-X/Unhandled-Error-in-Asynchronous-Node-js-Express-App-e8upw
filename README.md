# Unhandled Error in Asynchronous Node.js Express App

This repository demonstrates a common error in Node.js applications: unhandled errors within asynchronous callbacks.  The `bug.js` file contains an Express.js server that simulates an asynchronous operation.  Sometimes, this operation throws an error, resulting in an uncaught exception and the application crashing.

The solution, provided in `bugSolution.js`, shows how to properly handle such errors using `try...catch` blocks or the async/await pattern with error handling.