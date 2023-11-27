# Postman-API-Testing

Welcome to the Postman Collection for interacting with the API. This collection provides a set of HTTP requests using the GET, POST, and DELETE methods. Use this collection to test and understand the API functionalities.

Features
GET Request - Retrieve Data

Endpoint: /api/data
Expected Status Code: 200 OK
Description: Retrieve data from the API.
POST Request - Create Data

Endpoint: /api/data
Expected Status Code: 405 Method Not Allowed
Description: Attempt to create data (Note: The API does not allow POST requests on this endpoint).
DELETE Request - Delete Data

Endpoint: /api/data/{id}
Expected Status Code: 405 Method Not Allowed
Description: Attempt to delete data (Note: The API does not allow DELETE requests on this endpoint).
Getting Started
Clone the Repository: Clone or download this repository to your local machine.

bash
Copy code
git clone https://github.com/your_username/postman-collection.git
Import Collection into Postman:

Open Postman.
Click on "Import" and select the downloaded postman_collection.json file.
Environment Variables:

Define environment variables for base_url and any other required variables.
Set base_url to the base URL of your API.
Run Requests:

Run each request in the collection and observe the responses.
Verify that the GET request returns a 200 OK status.
Note the 405 Method Not Allowed status for both POST and DELETE requests.
Notes
Ensure your API is running and accessible before executing requests.
Review the API documentation for any additional details on expected behavior.
Happy testing with Postman!





