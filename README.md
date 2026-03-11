# API Testing Project – JSONPlaceholder (Postman)

## Project Overview

This project demonstrates API testing using Postman by testing public REST APIs from JSONPlaceholder. The goal of this project is to practice sending HTTP requests, understanding API behavior, and working with core API testing concepts such as HTTP methods, path parameters, query parameters, request bodies, and Collection variables.

## Tool Used

* Postman

## API Under Test

https://jsonplaceholder.typicode.com

JSONPlaceholder is a free fake REST API used for learning and testing API requests.

---

# API Requests Implemented

The following API requests were created and tested in Postman:

| Request Name     | Method | Endpoint           | Description                                     |
| ---------------- | ------ | ------------------ | ----------------------------------------------- |
| Get All Posts    | GET    | /posts             | Retrieve all posts                              |
| Get Single Post  | GET    | /posts/1           | Retrieve a specific post using a path parameter |
| Create Post      | POST   | /posts             | Create a new post using JSON request body       |
| Update Post      | PUT    | /posts/1           | Update an existing post                         |
| Delete Post      | DELETE | /posts/1           | Delete a specific post                          |
| Query Parameters | GET    | /comments?postId=4 | Retrieve comments using query parameter         |
| Path Parameters  | GET    | /posts/5           | Retrieve a specific post using path parameter   |

---

# API Concepts Practiced

This project covers the following API testing concepts:

* HTTP Methods (GET, POST, PUT, DELETE)
* Path Parameters
* Query Parameters
* JSON Request Body
* REST API Endpoints
* Postman Collections
* Collection Variables

---

# Collection Variable

An collection variable was used to store the base API URL.

Variable Name:

```text id="v1"
base-url
```

Example Value:

```text id="v2"
https://jsonplaceholder.typicode.com
```

Example Request Using Variable:

```text id="v3"
{{base-url}}/posts
```

Using collection variables helps maintain cleaner and more reusable API requests.

---

# Example Request Body

Example JSON body used in the **Create Post** request:

```json id="v4"
{
 "title": "API Testing",
 "body": "Learning Postman",
 "userId": 1
}
```

Example JSON body used in the **Update Post** request:

```json id="v5"
{
 "id": 1,
 "title": "Updated Post",
 "body": "API Testing with Postman",
 "userId": 1
}
```

---

# Project Structure

```text id="v6"
api-testing-postman-project
│
├── Postman_Collection
│   └── jsonplaceholder_api_testing_collection.json
│
└── README.md
```

---

# How to Use This Collection

1. Open Postman.
2. Click **Import**.
3. Upload the JSON collection file.
4. Set the Collection variable `base-url`.
5. Run the requests to test the API endpoints.

---

# Learning Outcome

Through this project, the following API testing skills were practiced:

* Sending HTTP requests using Postman
* Testing REST APIs
* Using path parameters and query parameters
* Working with JSON request bodies
* Using collection variables
* Organizing API requests into Postman collections

---

# Author
Created by Rasel.
