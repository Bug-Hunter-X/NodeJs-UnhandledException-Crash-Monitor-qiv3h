# Node.js Server Crash Bug

This repository demonstrates a bug causing intermittent crashes in a simple Node.js HTTP server.  The server is designed to respond with 'Hello, World!', but due to improper exception handling, it can fail unpredictably.

## Bug Description
The server crashes intermittently, and does not always return a response.  This is caused by a lack of robust error handling in the response generation.