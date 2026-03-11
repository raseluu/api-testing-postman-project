# API Testing Project – JSONPlaceholder API (Postman)

## Project Overview

This project demonstrates API testing using Postman by testing public REST APIs from JSONPlaceholder. The objective of this project is to practice sending HTTP requests, validating responses, and understanding core API testing concepts such as query parameters, path parameters, request bodies, and HTTP methods.

## Tool Used

* Postman

## API Under Test

https://jsonplaceholder.typicode.com

JSONPlaceholder provides a free fake REST API used for learning and testing API requests.

## API Requests Implemented

The following API requests were created and tested in Postman:

| Request Name     | Method | Endpoint           | Description                                   |
| ---------------- | ------ | ------------------ | --------------------------------------------- |
| Get All Posts    | GET    | /posts             | Retrieve all posts                            |
| Get Single Post  | GET    | /posts/1           | Retrieve a specific post using path parameter |
| Create Post      | POST   | /posts             | Create a new post using JSON request body     |
| Update Post      | PUT    | /posts/1           | Update an existing post                       |
| Delete Post      | DELETE | /posts/1           | Delete a specific post                        |
| Query Parameters | GET    | /comments?postId=4 | Retrieve comments filtered by query parameter |
| Path Parameters  | GET    | /posts/5           | Retrieve a post using path parameter          |

## API Concepts Practiced

This project covers the following API testing concepts:

* HTTP Methods (GET, POST, PUT, DELETE)
* Path Parameters
* Query Parameters
* JSON Request Body
* REST API Endpoints
* API Response Verification
* Postman Collections

## Example Request Body

Example JSON body used in the **Create Post** request:

```json
{
 "title": "API Testing",
 "body": "Learning Postman",
 "userId": 1
}
```

## Example Updated Request Body

Used in the **Update Post** request:

```json
{
 "id": 1,
 "title": "Updated Post",
 "body": "API Testing with Postman",
 "userId": 1
}
```

## Project Structure

```
api-testing-postman-project
│
├── Postman_Collection
│   └── jsonplaceholder_api_testing_collection.json
│
└── README.md
```

## How to Use This Collection

1. Open Postman.
2. Click **Import**.
3. Upload the JSON collection file.
4. Run the requests inside the collection to test the API endpoints.

## Learning Outcome

Through this project, the following API testing skills were practiced:

* Sending HTTP requests using Postman
* Testing REST APIs
* Using query parameters and path parameters
* Working with JSON request bodies
* Organizing API requests in Postman collections

## Author

Created by Rasel.
