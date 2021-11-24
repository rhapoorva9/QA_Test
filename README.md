# QA_Test

## How to run the app?

For security reasons, the provided JSON file is not directly read in the local machine.

Please run the following script in Python to run a local HTTP server to run the app.

```
python -m SimpleHTTPServer
Serving HTTP on 0.0.0.0 port 8000 ...
127.0.0.1 - - [23/Nov/2021 19:43:09] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [23/Nov/2021 19:43:10] "GET /sample.json HTTP/1.1" 200 -
```

Navigate to http://localhost:8000 to view the results.
