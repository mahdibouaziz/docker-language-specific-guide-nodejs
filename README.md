# docker-language-specific-guide-nodejs

### Server description

The mocking server is called Ronin.js and will listen on port 8000 by default. You can make POST requests to the root (/) endpoint and any JSON structure you send to the server will be saved in memory. You can also send GET requests to the same endpoint and receive an array of JSON objects that you have previously POSTed.
