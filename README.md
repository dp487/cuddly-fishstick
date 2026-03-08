# Project Description: Simple Web Server in Go

This project implements a basic web server using Go's `net/http` package. The server serves static files from a designated directory and provides two specific endpoints: `/form` and `/hello`.

## Features
- **Static File Serving**: The server serves static files from the `./static` directory, allowing for easy access to HTML, CSS, and JavaScript resources.
- **Form Handling**: The `/form` endpoint processes POST requests from a form, extracting `name` and `address` values from the submitted form data.
  - Returns a confirmation message along with the submitted name and address.
- **Hello Endpoint**: The `/hello` endpoint responds to GET requests with a simple "hello!" message. It also handles incorrect paths and methods by returning appropriate error messages.

## Usage
1. Start the server by running the Go application.
2. Access the static files by navigating to `http://localhost:8080/`.
3. To test the form handling, create a simple HTML form that submits data to `http://localhost:8080/form`.
4. Access the hello endpoint by navigating to `http://localhost:8080/hello`.

## Technologies Used
- Go (Golang)
- net/http package

This project serves as a foundational template for understanding HTTP request handling, form processing, and static file serving in Go.
