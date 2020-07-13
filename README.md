# Frontend Templates and Mock Customer Data
 
This repo contains a mock API server, which will serve data to your frontend app.

## Installation

To install the API server and its dependencies, run this command:

```npm install```

## Start the Server

To run the server, run this command: 

```npm run start-server```

The output should display the URL of the running server (e.g. http//localhost:3000).

## Usage

Once the server is running, you can access the list of customers at this URL:

Show customers : `GET /api/customers/`

Retrieve a customer by ID : `GET /api/customers/:id`

Retrieve a customer by email : `GET /api/customers/?email=:email`

Filter users by partial email : `GET /api/customers/?email_like=:partial_email`

See the json-server documentation for a full usage guide. 
