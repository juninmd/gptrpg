```markdown
# AGENTS.md Guidelines

These guidelines outline the principles and practices for developing AI coding agents within this repository.  Adherence to these principles is crucial for maintaining a well-structured, maintainable, and robust codebase.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent should have a single, well-defined purpose. Avoid creating agents with overly complex functionalities that serve multiple roles.
*   **Abstraction:** Design agents to be abstract, hiding implementation details behind well-defined interfaces.
*   **Code Reuse:**  Strive to create reusable components or modules that can be combined to build multiple agents.  Favor common patterns and algorithms.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimize Complexity:**  Keep agent logic as simple as possible. Avoid unnecessary complexity that degrades readability.
*   **Readability:**  Prioritize clear, concise, and well-formatted code. Use meaningful variable names and comments where necessary.
*   **Small, Focused Functions:**  Each function should have a single, well-defined purpose.

## 3. SOLID Principles

*   **Single Responsibility Principle:**  The agent should have a clear and stable responsibility.
*   **Open/Closed Principle:** The agent should be extensible without modifying the existing code.  New functionality should be added via APIs.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without affecting the correctness of the system.
*   **Interface Segregation Principle:** Client code shouldn’t be forced to depend on methods it doesn’t use.
*   **Dependency Inversion Principle:**  High-level modules (agents) should be dependent on low-level modules (interfaces), not vice versa.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Defer Implementation:**  Don't implement features or functionalities that are not currently required for the agent's purpose.
*   **Focus on Requirements:**  The primary goal is to fulfill the defined requirements.  Future needs should be considered, but not implemented.

## 5. Development Practices

*   **Unit Testing:** All agent code must be thoroughly unit tested.
*   **Code Review:**  All code should be reviewed by at least one other developer to ensure quality and consistency.
*   **Static Analysis:**  Utilize static analysis tools to identify potential issues and enforce coding standards.
*   **Documentation:**  Document agent interfaces, data structures, and algorithms.
*   **Parameterization:** Use parameterized agents whenever possible to enhance reusability and testability.

## 6. Code Size & Test Coverage

*   **Maximum Code Length:** Each file should be no more than 180 lines of code.
*   **Test Coverage Target:**  Achieve a minimum of 80% test coverage across all agent functions and modules. This includes unit tests and integration tests.
*   **Test Case Design:**  Ensure tests cover edge cases, boundary conditions, and potential error scenarios.

## 7.  File Structure & Conventions

*   **Modular Design:**  Organize code into logical modules, each with a clear purpose.
*   **Clear Naming Conventions:**  Use consistent naming conventions for variables, functions, and classes.
*   **Comments:**  Add concise comments to explain complex logic or non-obvious decisions.

## 8.  Data Handling

*   **Abstraction:**  Don’t expose internal implementation details of data structures.
*   **Encapsulation:**  Protect data through encapsulation to prevent accidental modification.

## 9.  API Design -  (For Agents with external contracts)

*   **Well-Defined Interfaces:**  Define clear, stable interfaces for all agent functionalities, using dependency injection or similar patterns.
*   **Versioning:**  Employ versioning for API changes.


These guidelines are intended as a reference for all development activities.  Ongoing monitoring and refinement will be essential for maintaining a high-quality codebase.
```