## Project Title

LittleLemon Webapp (Back-End Developer Capstone Project)

## Introduction

This project showcases the implementation of a backend API for a restaurant booking system. The API allows users to view menu items, make bookings, and manage user authentication. It's built using Django and Django REST framework, with JWT-based authentication for securing the API.

## API Endpoints

- '/api/bookings/': Retrieve, create, update, and delete bookings.
- '/api/menu-items/': Retrieve menu items.
- '/api/token/login/': Obtain JWT token for authentication.
- '/api/token/refresh/': Refresh JWT token.

## Testing the API

To test the API, you can use tools like Insomnia or Postman. Ensure that you obtain a JWT token using the `/api/token/login/` endpoint and include it in the Authorization header for requests to protected endpoints.

## Notes

Update this README file with any additional setup or configuration instructions as needed.
