
## Description

This project builds a backend web service for a simple bank. It will provide APIs for the frontend to do the following things:

* Create and manage bank accounts.
* Record all balance changes to each of the accounts.
* Perform a money transfer between 2 accounts.

## Techstack:

* Designed and developed DB using PostgreSQL. Implemented transactions following ACID properties.
* Built a set of RESTful HTTP APIs using Gin - one of the most popular Golang frameworks for building web services. This includes everything from loading app configs, mocking DB for more robust unit tests, handling errors, authenticating users, and securing the APIs with JWT and PASETO access tokens.

