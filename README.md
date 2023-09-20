## Book Api testing

## Description
This project aims to demonstrate how to interact with book-related APIs using Python and Postman. It covers various methods to retrieve, create, and update book data through these APIs.

## Usage

### Testing with Python

1. Open your Python terminal.
2. Navigate to the project directory.
3. Run the Python codes for API testing:


```
python3
```
 To open an interactive interpreter, allowing you to run Python code interactively, providing a command-line interface where you can execute Python statements one at a time.
```
import requests
```
 By importing requests, you make its functions and classes available for use in your Python code
```
response = requests.get('https://simple-books-api.glitch.me')
```
 the requests.get() method  is used to send an HTTP GET request to the URL 'https://simple-books-api.glitch.me'.The response from the server is stored in the variable response. This response object contains information about the HTTP response, including the status code, headers, and content.
```
print(response)
```
 prints the response object to the console. This will display information about the HTTP response, including the status code, which indicates whether the request was successful and other details like headers and content.

Expected Python shell output:
file:///home/moringa/Screenshots/Screenshot%20from%202023-09-19%2015-26-05.png



### Testing with Postman

1. Open Postman.
2. Import the provided collection file for testing.
3. Use the collection to send requests to various book-related APIs.
4. Capture and document the results with images.

## Technology Used
+ Python
+ Postman
+ API Testing
+ Git/GitHub
+ Markdown

## Author
+  Anita Mutemi
+ Naomi Cherono
