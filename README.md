## Calculator Service with Hapi.js
This project is a simple calculator service implemented using Hapi.js framework. It provides basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Getting Started
To run the calculator service locally, follow these steps:

## Clone the repository:

git clone <repository-url>

## Install dependencies:

cd <project-directory>
npm install
Start the server:
npm start

The server will be up and running at http://localhost:4000.

## Endpoints

## About Route

Path: /calculator/about
Method: GET
Description: Provides information about the calculator service.

## Addition Route

Path: /calculator/add/{num1}/{num2}
Method: GET
Description: Performs addition of two numbers.

## Subtraction Route

Path: /calculator/sub/{num1}/{num2}
Method: GET
Description: Performs subtraction of two numbers.

## Multiplication Route

Path: /calculator/mul/{num1}/{num2}
Method: GET
Description: Performs multiplication of two numbers.

## Division Route

Path: /calculator/div/{num1}/{num2}
Method: GET
Description: Performs division of two numbers. Handles division by zero error.
Example Route
Example Route

Path: /example
Method: GET
Description: Returns a simple "Hello, world!" message.
## Usage
You can use the provided routes to perform basic arithmetic operations. Simply make HTTP requests to the specified endpoints with appropriate parameters.

Feel free to explore and integrate this calculator service into your projects!
## License
This project is licensed under the MIT License - see the LICENSE file for details.
