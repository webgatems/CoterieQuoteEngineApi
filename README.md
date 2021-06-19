# CoterieQuoteEngineApi

### API Instructions and Notes

* The api post URL is: https://localhost:44339/api/v1/QuoteEngine

* While Postman can be used to test the Api, Swagger is wired up and will run automatically.

* Test the input values (Revenue, State, Business) with faulty values to observe basic error handling.

* A few simple unit tests have been added and can be executed using the normal Test Explorer. These tests were written using the Machine.Specifications packages to encourage TDD and BDD.

### Next Steps

1. Implement Logging

1. Move Controller business logic into a Service class

1. Fetch State Factors and Business Factors from data repository

1. Tighten premium calculation with more thorough error detection and handling 

1. Add more unit tests

1. Add API integration tests

1. Implement CORS rules

1. Implement Authentication and Authorization using JWT Auth (Roles, Claims, Lifetime, etc.)

1. Implement health monitoring
