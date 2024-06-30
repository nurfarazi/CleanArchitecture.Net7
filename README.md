#Clean architecture with .NET 7

This is a simple example of how to implement a clean architecture with .NET 7. The project is a simple API that allows you to create, read, update and delete. The project is divided into 4 layers:

- **API**: This is the entry point of the application. It is responsible for receiving the requests and returning the responses. It is a simple REST API built with ASP.NET Core.
- **Application**: This layer contains the application logic. It is responsible for handling the business rules and orchestrating the flow of data between the other layers.
- **Domain**: This layer contains the domain logic. It is responsible for defining the entities and the business rules of the application.
- **Infrastructure**: This layer contains the infrastructure logic. It is responsible for interacting with external services, such as databases and APIs.