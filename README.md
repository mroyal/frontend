# Frontend Template Edit/Preview
 
This repo contains a mock API server, which will serve data to your frontend app.

## Installation

To install the API server and its dependencies, run this command:

```npm install```

## Usage

To run the server, run this command: 

```json-server --watch data/customers.json```

Once the server is running, you can access the list of customers at this URL:

    http://localhost:3000/customers/

To access the data for an individual customer, append the customer's ID to the endpoint. For example:

    http://localhost:3000/customers/7efa4432bfe4
