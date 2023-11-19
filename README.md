# Simple Static Web Server in Go

This is a basic static web server implemented in Go that serves static files from the "static" directory, handles a simple "/hello" endpoint, and processes a form submission at "/form".

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Sarthak027/Webserver_made_with_GOLANG.git
1. Navigate to the directory;
    ```bash
    cd Webserver_made_with_GOLANG
2. run the GO application:
     ```bash
     go run main.go
This will start the server on http://localhost:8080
## Endpoints
** `/hello`: Responds with a simple "hello!" message for GET requests.

** `/form`: Handles form submissions and displays the submitted data for POST requests.
     
