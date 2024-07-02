
# Clean Architecture Project (.NET 7)

Welcome to this Clean Architecture project! This repository demonstrates a scalable and maintainable architecture for
building .NET 7 applications. By strictly adhering to the principles of Clean Architecture.

## Key Features & Benefits

* **Separation of Concerns:** Each component has a distinct responsibility, enhancing modularity and testability.
* **Testability:** Automated tests are integrated at all layers, ensuring code quality and robustness.
* **Maintainability:**  Changes are isolated, minimizing the impact on other parts of the system.
* **Framework Agnosticism:** The core business logic remains independent of UI frameworks and databases, enabling
  greater flexibility.
* **Dependency Inversion:** High-level modules are not dependent on low-level modules; both depend on abstractions.

## Project Structure

* **Api:**  Contains controllers, entry points for external requests, and orchestrates application behavior.
* **Application:** Houses core business logic, use cases, and application services.
* **Domain:** Defines the core business entities, value objects, and the language of the business domain.
* **Infrastructure:** Implements details related to external dependencies (e.g., database access, external services).
* **Presentation:** Handles UI logic and user interactions (e.g., views, view models).

## Getting Started

1. **Prerequisites:**
    * [.NET 7 SDK](https://dotnet.microsoft.com/download)
   
2. **Clone the Repository:**

   ```bash
   git clone https://<repo>.git
   cd your-project-name
   ```

3. **Build and Run:**

   ```bash
   dotnet build
   dotnet run --project Api 
   ```

## Configuration

* Adjust connection strings or other settings in `appsettings.json` files within the `Api` and `Infrastructure`
  projects.
* Customize logging, caching, and other cross-cutting concerns in the `Startup.cs` files.