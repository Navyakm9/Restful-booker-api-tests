# Restful Booker API - Postman Test Suite

This project contains API  test cases for the [Restful Booker API](https://restful-booker.herokuapp.com/) using Postman and includes both **positive** and **negative** test scenarios.

##  Project Contents

| File Name                                                 | Description                                 |
|-----------------------------------------------            |---------------------------------------------|
| `bookerrestful.postman_collection`                        | Main Postman collection with test scripts   |
| `bookerrestful Negative testcases.postman_collection`     | Collection with negative test scenarios      |
| `booker.postman_environment`                              | Environment file with base URL/token vars   |
| `TestCase_restfulbooker.xlsx`                             | Manual test case documentation (Excel)      |

##  Test Coverage

- `POST /booking` (Create booking)
- `GET /booking` and `/booking/:id`
- `PUT /booking/:id` (Update booking)
- `DELETE /booking/:id`
- Positive and negative validations using test scripts

##  How to Run

1. Import the collection and environment files into Postman.
2. Set the base URL in the environment (e.g., `https://restful-booker.herokuapp.com`).
3. Use `Send` or run the full collection using Collection Runner.

## Tools used
1.POSTMAN
2.GIT hub

## Author
**Navyakm9**

