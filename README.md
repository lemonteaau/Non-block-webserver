# Simple HTTP Non-block Server

## Overview
A simple non-block webserver based on CNA course assignment from University of Adelaide.
It's designed to handle basic web server functionality, including accepting client requests and serving HTML files. The server handles different types of HTTP requests and responds appropriately based on the request type and resource availability.

## Features
- **HTTP Request Handling**: Parses incoming HTTP requests and extracts essential information like method, URI, and HTTP version.
- **Response Generation**: Generates appropriate HTTP responses based on the request type and resource status.
- **Resource Serving**: Serves static HTML files from a specified directory.
- **Method Support**: Supports GET and HEAD methods; other methods return a '501 Not Implemented' response.
- **Error Handling**: Properly handles bad requests and non-existent resources with '400 Bad Request' and '404 Not Found' responses, respectively.
